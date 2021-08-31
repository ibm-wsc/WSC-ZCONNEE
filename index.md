<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) workshop. 

The WSC's z/OS Connect EE Getting Started Guide can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/zOS%20Connect%20EE%20V3%20Getting%20Started.pdf){:target="_blank"} to view it locally.
  
The WSC's z/OS Connect EE Advanced Topics Guide can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/security/zOS%20Connect%20EE%20V3%20Advanced%20Topics%20Guide.pdf){:target="_blank"} to view it locally.

Click [here](ZCONNEE - Introduction to zOS Connect EE.pdf){:target="_blank"} to download the presentation.

## Accessing the hands-on lab

Click [here](Remote Desktop Windows.pdf){:target="_blank"} to read the instruction for Remote Desktop access.

All lab instructions are in the "Lab Docs" folder on your remote desktop, or can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/exercises){:target="_blank"} to view it locally.

The server XML configuration files referenced in the exercises can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/xml){:target="_blank"} to view it locally.


**Please enter your email address used for registration to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

## Help 
Having trouble with labs? Send an email to [Eric Higgins](mailto: higgins@us.ibm.com), [Chris Griego](mailto: cgriego@us.ibm.com) or [Mitch Johnson](mailto: mitchj@us.ibm.com) and we will help you sort it out.
