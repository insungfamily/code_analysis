일반 클래스


<--현재 사용 중-->
	using System.Diagnostics;
	using System.Text;
	using SwVsPaint.Vision;
	using MaterialSkin.Controls;
	using OpenCvSharp;
	using Point = OpenCvSharp.Point;
	using Size = OpenCvSharp.Size;

<--현재 미 사용 중-->
	using System;
	using System.Collections.Generic;
	using System.ComponentModel;
	using System.Data;
	using System.Drawing;
	using System.Linq;
	using System.Threading.Tasks;
	using System.Windows.Forms;
	using Accord;
	using OpenCvSharp.Extensions;


<--생성자-->
	=> [[Form/FTestOption_Form/1. 초기화 및 설정/__초기화 및 설정__|__초기화 및 설정__]]


<--멤버 함수--> [[Form/FTestOption_Form/2. 동작/__동작__|__동작__]]
	private void InitialzeValue()
	private void CheckRoiList()
	private void btnBinary_Click(object sender, EventArgs e)
	private void btnHistEqual_Click(object sender, EventArgs e)
	private void btnCannyEdge_Click(object sender, EventArgs e)
	private void btnSobelVer_Click(object sender, EventArgs e)
	private void btnSeparGray_Click(object sender, EventArgs e)
	private void btnLabel_Click(object sender, EventArgs e)
	private void btnLabelSeq_Click(object sender, EventArgs e)
	private void cobxRoiIndex_MouseDown(object sender, MouseEventArgs e)
	private void cobxRoiIndex_SelectionChangeCommitted(object sender, EventArgs e)
	private void btnOpening_Click(object sender, EventArgs e)
	private void btnClosing_Click(object sender, EventArgs e)
	private void btnErode_Click(object sender, EventArgs e)
	private void btnDilate_Click(object sender, EventArgs e)
	private void btnFilterGaussian_Click(object sender, EventArgs e)
	private void btnUnSharpening_Click(object sender, EventArgs e)
	private void btnSharpening_Click(object sender, EventArgs e)
	private void btnBilateral_Click(object sender, EventArgs e)
	private void btnGetOrigin_Click(object sender, EventArgs e)
	private void btnDist_Click(object sender, EventArgs e)
	private void btnFindContour_Click(object sender, EventArgs e)
	private void btnTempMatch_Click(object sender, EventArgs e)
	private void btnShapeMatch_Click(object sender, EventArgs e)
	private void FTestOption_FormClosing(object sender, FormClosingEventArgs e)
	private void btnContrast_Click(object sender, EventArgs e)
	private static double Clip(double value, double min, double max)
	private void btnMedianFilter_Click(object sender, EventArgs e)
	private void btnSaveMasking_Click(object sender, EventArgs e)
	private void btnApplyMask_Click(object sender, EventArgs e)
	private void btnShowMask_Click(object sender, EventArgs e)
	private void btnTestInsp_Click(object sender, EventArgs e)
	private Mat DetectAndBinariazeObjects(Mat inputImage)
	private void btnApplyMaskAND_Click(object sender, EventArgs e)
	private void btnApplyMaskOR_Click(object sender, EventArgs e)
	private void btnColorEqauliz_Click(object sender, EventArgs e)
	private Mat EqualizeColorImage(Mat inputImage)
	private void btnTestInsp2_Click(object sender, EventArgs e)
	private void btnDrawEllipse_Click(object sender, EventArgs e)
	private void btnClearEllipse_Click(object sender, EventArgs e)