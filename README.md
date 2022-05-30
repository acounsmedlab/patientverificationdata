<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.patientData {
border-collapse: collapse;
border-spacing: 0;
width: 100%;
border: 1px solid #ddd;
font-size: 13px;
}
table.patientData td {
padding: 4px;
}
.patientResultData {
border-collapse: collapse;
border-spacing: 0;
width: 100%;
border: 1px solid #ddd;
font-size: 13px;
}
.patientResultInvestigation {
padding: 4px;
background-color: #f2f2f2;
color: red;
}
table.patientResultData td{
padding: 4px;
color: #595959;
}
</style>
</head>
<title>EasyMedical - Patient verfication data</title>
<body style="background-color:white" onload="javascript:m_onload();" onmouseup="javascript:bodyOnClick(event)">
<script>
function getScrollBottom(p_oElem){
return p_oElem.scrollHeight - p_oElem.scrollTop - p_oElem.clientHeight;
}
function m_onload(){
}
function bodyOnClick(e){
}
</script>
<!-- de aici incepepagina-->
<script>
function formOnClick(tag){
}
</script>
<form id="mForm" name="mForm" onclick="javascript:formOnClick(this)" action="" method="" >
<div>
<img src="https://cloud.easymedical.ng/eAcouns/images/Client/acouns_Logo.jpg" style="width: 125px;">
</div>
<hr>
<br><br>
<div align="center"><b>PATIENT VERIFICATION DATA</b></div>
<br>
<div style="overflow-x:auto;">
<table width="100%" class="patientData">
<tr>
<td align="left" nowrap><b>Patient name:</b></td>
<td>FRANCIS UKPOLO</td>
</tr>
<tr>
<td align="left" nowrap><b>Laboratory code:<b/></td>
<td>300002564</td>
</tr>
<tr>
<td align="left" nowrap><b>Collection date:</b></td>
<td>30/05/2022 10:12</td>
</tr>
</table>
<br>
<table width="100%" class="patientResultData">
<tr>
<th align="center" nowrap><b>Analyse</b></th>
<th align="center" nowrap >Result</th>
</tr>
<tr>
<td class="patientResultInvestigation" align="left" nowrap colspan="2"><b>1. COVID-19 PCR <b/></td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>COVID-19 PCR <b/></td>
<td align="center" style="font-size: 12px;">NEGATIVE</td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>RdRP Gene<b/></td>
<td align="center" style="font-size: 12px;">0.000</td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>N Gene<b/></td>
<td align="center" style="font-size: 12px;">0.000</td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>E Gene<b/></td>
<td align="center" style="font-size: 12px;">0.000</td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>IC<b/></td>
<td align="center" style="font-size: 12px;">29.350</td>
</tr>
<tr>
<td align="left" nowrap style="font-size: 12px;"><b>Comment<b/></td>
<td align="center" style="font-size: 12px;">Negative result indicates the absence of SARS-CoV2 RNA in the sample at the time of testing.<br>Continuous exposure to an infected person or persons can make an individual test positive after a previous negative result.</td>
</tr>
</table>
<div>
</form>
</body>
</html>
