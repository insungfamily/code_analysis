싱글 톤 다자인

<--현재 사용 중-->
	using Newtonsoft.Json;
	using MaterialSkin.Controls;
	using JsonFormatting = Newtonsoft.Json.Formatting;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.ComponentModel;
	using System.Data;
	using System.Drawing;
	using System.IO;
	using System.Linq;
	using System.Text;
	using System.Threading.Tasks;
	using System.Windows.Forms;


<--생성자-->
	=> [[Form/FMtrParam_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]

<--멤버 함수--> [[Form/FMtrParam_Form/2. 동작/__동작__|__동작__]]
	private void btnSave_Click(object sender, EventArgs e)
	private void btnLoad_Click(object sender, EventArgs e)
	public void SaveMtrParam(TabControl tabControl, string filePath)
	public void LoadMtrParam(TabControl tabControl, string filePath)
	private void SetControlValues(Control parent, Dictionary<string, double> settings)
	private void FMtrParam_FormClosing(object sender, FormClosingEventArgs e)





