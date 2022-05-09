 # Hand Gesture Detection Walkthrough
<p>A flutter application dependes on tenserflow lite module.It detects hand gesture then translate theses signs into descrptive text.</p> 
## Getting Started

### Setup 
<br />
<b>Step 1.</b> Clone this repository
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 5.</b> Detect gesture in real time using a webcam or using Images using the notebook <a href="https://github.com/LamaTarek/Hand_Gesture_Detection_App/blob/main/2.%20Training%20and%20Detection.ipynb">2.  Training and Detection.ipynb</a> - ensure you change the kernel to the virtual environment
<br/>

<img src="https://imgur.com/a/svG9EIp.png">
