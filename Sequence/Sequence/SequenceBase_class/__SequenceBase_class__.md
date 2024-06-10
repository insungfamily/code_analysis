
public abstract class SequenceBase

상속받은 클래스 목록
-  [[__DistortionSequence_class__]]
- [[__VisionSequence_class__]]
-  [[__MotorSequence_class__]]

<--생성자-->
	=> [[Sequence/Sequence/SequenceBase_class/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수-->[[Sequence/Sequence/SequenceBase_class/2. 동작/__동작__|__동작__]]
	protected void AddStep(string stepName, Func<CancellationToken, Task> stepAction)
	public async Task Start(CancellationToken cancellationToken)
	protected async Task NextStep(CancellationToken cancellationToken, int delay = 1)
	protected async Task MoveStep(int stepIndex, CancellationToken cancellationToken, int delay = 1)
	public int GetCurrentStateIndex()
	public bool IsStarted()
	public List<string> GetSteps()
	public string GetStepName(int index)
	protected void LogSequence(string message)