# Generate Analytics Report
<img src="resources/cover_page.jpg" alt="Analytics Report" width="300"/>
In this project, I've used data from Johns Hopkins' CSSEGI repository to create a report on Covid-19 cases in the USA and in South America.
<br/>
<br/>

## Setup
You'll want to download all of this code locally. The easiest way to do that is cloning the repo.
```
$ git clone https://github.com/yncosta/generate-analytics-report.git
```
If you have any trouble doing this, you can download the zip folder of this repo and then extract the files to a local file. Once you have all the files cloned locally, you should make sure you have all the necessary libraries installed.
```
$ pip install fpdf
$ pip install pandas numpy matplotlib
$ pip install plotly
$ pip install -U kaleido
```
If you run into an error with NumPy, changing the version to 1.19.3 fixed the issue for me
```
$ pip install numpy==1.19.3
```
To test if everything is set up properly, try running `python generate_report.py`. You should get a fresh report file. 
