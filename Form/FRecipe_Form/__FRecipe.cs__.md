싱글 톤 디자인

<--현재 사용 중-->
	using System.Text.Json;
	using MaterialSkin.Controls;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.IO;
	using System.Windows.Forms;


<--생성자-->
	=> [[Form/FRecipe_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]

<--멤버 함수--> [[Form/FRecipe_Form/2. 동작/__동작__|__동작__]]
	private void FRecipe_FormClosing(object sender, FormClosingEventArgs e)
	private void LoadCategoriesFromJsonFile(string jsonFilePath)
	private void InitializeComboBoxes()
	private void CbCategoryFirst_SelectedIndexChanged(object sender, EventArgs e)
	private void CbCategorySecond_SelectedIndexChanged(object sender, EventArgs e)
	private void btnCancel_Click(object sender, EventArgs e)
	private void cbCategoryThird_SelectedIndexChanged(object sender, EventArgs e)