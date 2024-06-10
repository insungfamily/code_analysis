SequenceBase 상속 받음

<--생성자-->
	=> [[Sequence/Sequence/SequenceBase_class/VisionSequencr_class/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]

<--멤버 함수-->  [[Sequence/Sequence/SequenceBase_class/VisionSequencr_class/2. 동작/__동작__|__동작__]]
	public Task StartVisionSequence(CancellationToken cancellationToken)
	private async Task Vision_Init(CancellationToken cancellationToken) // 0
	private async Task Vision_SnapCamera(CancellationToken cancellationToken) // 1
	private async Task Vision_Inspection(CancellationToken cancellationToken) // 2
	private async Task Vision_WaitInspection(CancellationToken cancellationToken) //3
	private async Task Vision_End(CancellationToken cancellationToken) //4