일반 클래스

<--현재 사용 중-->
	using SwVsPaint.Sequence;
	using MaterialSkin.Controls;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.Drawing;
	using System.Linq;
	using System.Threading.Tasks;
	using System.Windows.Forms;


<--생성자-->
	=> [[Sequence/FSeqMonitor_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수--> [[Sequence/FSeqMonitor_Form/2. 동작/__동작__|__동작__]]
private void InitializeDataGridView()
private void AddSequenceRows(string sequenceType, List<string> steps, Func<int, string> getStepName)
private void UpdateDataGridView(object sender, EventArgs e)
private void UpdateSequenceStatus(string sequenceType, int currentStepIndex, bool isStarted)
private void ToggleButtons(bool enable)
private async void btnSeq1_Click(object sender, EventArgs e)
private async void btnSeqAll_Click(object sender, EventArgs e)