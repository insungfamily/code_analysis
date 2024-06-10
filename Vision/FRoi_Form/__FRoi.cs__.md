싱글 톤으로 디자인 됨

<--현재 사용 중-->
	using System.ComponentModel;
	using OpenCvSharp;
	using Point = OpenCvSharp.Point;
	using MaterialSkin.Controls;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.Data;
	using System.Drawing;
	using System.Linq;
	using System.Text;
	using System.Threading.Tasks;
	using System.Windows.Forms;
	using Size = System.Drawing.Size;

<--생성자-->
	=> [[Vision/FRoi_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]

<--중첩 클래스-->
	public class RoiData
	{
	    public int Index { get; set; }
	    public int LeftTopX { get; set; }
	    public int LeftTopY { get; set; }
	    public int RightBottomX { get; set; }
	    public int RightBottomY { get; set; }
	}

<--멤버 함수--> [[Vision/FRoi_Form/2. 동작/__동작__|__동작__]]
	private void InitializeDataGridView()
	private void FRoi_FormClosing(object sender, FormClosingEventArgs e)
	private void btnNewRoi_Click(object sender, EventArgs e)
	public void SetRoi(Point ptLftTop, Point ptRgtBtm)
	public Rect GetRoi()
	public int GetRoiIndexNo()
	public Rect GetIndexRoi(int rowIndex)
	private void btnDelRoi_Click(object sender, EventArgs e)
	private void btSaveRoiData_Click(object sender, EventArgs e)
	public void LoadRoiData()
	public void SaveRoiData()
	public void DeleteRoiData(DataGridView dgv)