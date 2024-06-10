싱글 톤으로 디자인 됨

<--현재 사용 중-->
	using Newtonsoft.Json;
	using MaterialSkin.Controls;
	using JsonFormatting = Newtonsoft.Json.Formatting;
	using SwVsPaint.Sequence;

<--현재 미 사용 중-->
	없음


<--생성자-->
	=> [[Form/FVisParam_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수--> [[Form/FVisParam_Form/2. 동작/__동작__|__동작__]]
	private void btnSave_Click(object sender, EventArgs e)
	private void btnLoad_Click(object sender, EventArgs e)
	public void SaveVisParam(TabControl tabControl, string filePath)
	public void LoadVisParam(TabControl tabControl, string filePath)
	private void SetControlValues(Control parent, Dictionary<string, double> settings)
	private void FVisParam_FormClosing(object sender, FormClosingEventArgs e)
	private void btnGetRoi_Click(object sender, EventArgs e)
	private async Task WaitForCalibrationToFinish()
	private async void btnCamCalib_Click(object sender, EventArgs e)
	private async void btnGetMmpp_Click(object sender, EventArgs e)