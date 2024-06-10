<--현재 사용 중-->
	using Newtonsoft.Json;
	using MaterialSkin.Controls;
	using SwVsPaint.Motion;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.ComponentModel;
	using System.Data;
	using System.Drawing;
	using System.Linq;
	using System.Text;
	using System.Threading.Tasks;
	using System.Windows.Forms;

<--생성자-->
	=> [[Motion/FMotion_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수--> [[Motion/FMotion_Form/2. 동작/__동작__|__동작__]]
	private void InitMotion()
	private void InitProperty()
	public void AddAxisInfo()
	private void FMotor_FormClosing(object sender, FormClosingEventArgs e)
	private void rbMtrKindAbs_CheckedChanged(object sender, EventArgs e)
	private void rbMtrKindInc_CheckedChanged(object sender, EventArgs e)
	private void rbMtrKindBoth_CheckedChanged(object sender, EventArgs e)
	private void btnSave_Click(object sender, EventArgs e)
	private void btnLoad_Click(object sender, EventArgs e)
	public void SaveMtrParam(GroupBox groupBox, string filePath)
	public void LoadMtrParam(GroupBox groupBox, string filePath)
	private void cbUseControlMode_CheckedChanged(object sender, EventArgs e)