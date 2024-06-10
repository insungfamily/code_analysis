싱글 톤 디자인 사용됨

<--생성자-->
	=> [[Sequence/Sequence/SequenceMain_class/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수--> [[Sequence/Sequence/SequenceMain_class/2. 동작/__동작__|__동작__]]
	public async Task StartSeqMtrMoveAsync()
	public async Task StartSeqVisMoveAsync()
	public async Task StartSeqDistortionAsync()
	public async Task StartAllSequencesAsync()
	public void StopAllSequences()
	private async Task StartSequenceAsync(SequenceBase sequence, CancellationToken token)