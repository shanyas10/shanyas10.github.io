---
layout: page
permalink: /research/
title: Research
---


<h2>Publications</h2>
A complete list of my publications can also be found on my <a href = "https://scholar.google.com/citations?user=ypCFnQ8AAAAJ&hl=">Google Scholar profile.</a>
<ul>
	<li>
		<b>Evaluating Gender Bias in NLI System</b><br>
		<i>Sharma Shanya, <a href = "https://in.linkedin.com/in/manandey">Dey, Manan</a>, <a href = "https://www.cs.mcgill.ca/~ksinha4/">Sinha, Koustuv</a></i><br>
		NeurIPS 2020 Workshop on Dataset Curation and Security, 2020<br>
        <!-- Gender-bias stereotypes have recently raised significant ethical concerns in natural language processing. However, progress in detection and evaluation of gender-bias in natural language understanding through inference is limited and requires further investigation. In this work, we propose an evaluation methodology to measure these biases by constructing a challenge task which involves pairing gender neutral premise against gender-specific hypothesis. We use our challenge task to investigate state-of-the-art NLI models on the presence of gender stereotypes using occupations. Our findings suggest that three models (BERT, RoBERTa, BART) trained on MNLI and SNLI datasets are significantly prone to gender-induced prediction errors. We also find that debiasing techniques such as augmenting the training dataset to ensure a gender-balanced dataset can help reduce such bias in certain cases. <br> -->
		<a href="https://github.com/shanyas10/Evaluating-gender-bias/blob/master/Paper.pdf"><div class="color-button">Paper</div></a>
	</li><br>
	<li>
		<b>Assessing viewer’s mental health by detecting depression in youtube videos</b><br>
		<i>Sharma Shanya, <a href = "https://in.linkedin.com/in/manandey">Dey, Manan</a></i><br>
		 NeurIPS 2019 AISG Workshop, 2019<br>
		<!-- Depression is one of the most prevalent mental health issues around the world, proving to be one
        of the leading causes of suicide and placing large economic burdens on families and society. In
        this paper, we develop and test the efficacy of machine learning techniques applied to the content of
        YouTube videos captured through their transcripts and determine if the videos are depressive or have a
        depressing trigger. Our model can detect depressive videos with an accuracy of 83%. We also introduce
        a real-life evaluation technique to validate our classification based on the comments posted on a video
        by calculating the CES-D scores of the comments. This work conforms greatly with UN Sustainable
        Goal of ensuring Good Health and Well Being with major conformity with section UN SDG 3.4.<br> -->
		<a href="https://aiforsocialgood.github.io/neurips2019/accepted/track1/pdfs/52_aisg_neurips2019.pdf"><div class="color-button">Paper</div></a>
	</li><br>
	<li>
		<b>Building scalable mobile edge computing by enhancing quality of services</b><br>
		<i><a href = "https://scholar.google.co.in/citations?user=xtMDCsQAAAAJ&hl">Tiwary Mayank</a> Sharma Shanya, <a href = "https://scholar.google.co.in/citations?user=Tjmnc3sAAAAJ&hl">Mishra, Pritish</a></i><br>
		 International Conference on Innovations in Information Technology (IIT), 2018<br>
         <!-- With the new computing archutecture supported by Mobile Edge Computing (MEC) brings services to the physical proximity of end users, resource rich mobile devices such as smartphones can now offer computational services to another smartphones. Leveraging the computational resources from mobile cloudlet clusters the availability of mobile nodes is the most important attribute. The effect of movement of mobile devices in real life scenarios has not been captured reliably. This work focuses on improving the Quality of Service (QoS) by considering the effect of mobility deviation. This paper presents an dynamic pricing model which calculates the deviation of the contributors and optimises the price depending on the demand-supply curve. Finally, the proposed scheme is simulated in NS3 environment and is compared with existing schemes to validate the performance of proposed scheme. We observe that there is a proposed steep increase in overall utility in terms of response time and resource utilization with the proposed scheme.<br> -->
		<a href="https://ieeexplore.ieee.org/abstract/document/8605955"><div class="color-button">Paper</div></a>
	</li><br>
</ul>

<h2>Research Projects</h2>
You can also check out my <a href="https://github.com/shanyas10">Github profile</a> for a complete list of my projects.
<ul>
	<li>
		<b>Peer-to-peer AI-based tracing of COVID-19</b><br>
		Contributed to the simulator of Peer-to-Peer AI Tracing App delegated by Prof. Yoshua Bengio. The simulator simulates human mobility along with COVID-19 spreading in a city, while considering a city to consist of houses, grocery stores, parks, workplaces, and other non-essential establishments. Contributed on simulating mobility by simulating number of houses, stores, parks in a city. (Please note that my github handle, mentioned as @thechange in the repository, has been changed to @shanyas10).<br>
		<a href="https://mila.quebec/wp-content/uploads/2020/05/COVI-whitepaper-V1.pdf"><div class="color-button">Report</div></a>
		<a href="https://github.com/pg2455/covid_p2p_simulation"><div class="color-button">Code</div></a>
	</li><br>
	<li>
		<b>Using Affective Computing to analyze YouTube watching history to detect depression</b><br>
		The project is based on the theory Misery loves company, i.e. in misery we tend to consume content such as music, literature etc. that we relate to. It is aimed at calculation of affective scores of videos using the audio visual feature and further analyzing the affective pattern generated from the YouTube watching history of an individual to predict his depression severity score.<br>
		<a href="http://thechange.tech/"><div class="color-button">Report</div></a>
	</li><br>
	<li>
		<b>Detection of fake news during disasters</b><br>
		False and incorrect information during disasters can lead to chaos and panic among people on the ground and have serious detrimental outcomes for public safety.In this project, I developed a multi-modal model using BiLSTM-CHarCNN and VGG 16 that can detect the credibility of a post by effectively capturing the semantics of the text along with the features of associated piece of multimedia in it.<br>
		<a href="https://github.com/shanyas10/Fake-News-Detection/blob/master/Paper.pdf"><div class="color-button">Report</div></a><a href="https://github.com/shanyas10/Fake-News-Detection"><div class="color-button">Code</div></a>
	</li><br>
	<li>
		<b>Extractive Summarizer</b><br>
		Developed an extraction based document summarizing application which automatically summarizes the text given by choosing the important sentences in the document.Used Naive Bayes classifierto train the model using certain statistical features- based on the frequency of some elements in text and linguistic features- based on the structure of text(length and position).<br>
		<a href="https://github.com/shanyas10/SUMA-The-Summarizer"><div class="color-button">Code</div></a>
	</li><br>
	<li>
		<b>Real-time facial emotion detector</b><br>
		(Major project for B.E. final year)
		Developed a facial emotion classifier using SVM to classify a facial expression as happy, sad or surprised with an accuracy of 73%. Used Viola Jones Algorithm for facial detection and Local Binary Patterns(LBP) for feature extraction. Cohn-Kanade dataset for training and evaluation purpose. To test the out-of-domain accuracy, an additional evaluation dataset of 100 images by capturing facial expressions of 5 volunteers. OOD accuracy came out to be 68%. Integrated with Arduino UNO to capture the output signal from MATLAB and display the detected emotion on 16x2 LCD<br>
		<a href="https://github.com/shanyas10/SUMA-The-Summarizer"><div class="color-button">Code</div></a>
	</li><br>
</ul>

<h2>Reviewer</h2>
<ul>
	<li>
	Neural Information Processing Systems (NeurIPS) 2020
	</li><br>
	
	<li>
	NeurIPS Machine Learning For Health Workshop (ML4H) 2020
	</li><br>

	<li>
	ACM Conference on Health, Inference and Learning (CHIL)
	</li><br>
	
	<li>
	NeurIPS Machine Learning For Health Workshop (ML4H) 2019
	</li><br>
</ul>
<!-- <h2>Research Implementations</h2>
<ul>
	<li>
		<b>Title #1</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>Title #2</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul> -->