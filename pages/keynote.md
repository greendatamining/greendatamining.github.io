---
layout: page
title: Keynote Speaker
permalink: /keynote/
feature-img: "assets/img/workshop/green3.jpg"
---
<h1 style="text-align: center">Keynote Speakers</h1>

<hr>
<div>
        <div style="width:20%; float:left">
			<img src="../assets/img/pete_warden.png" alt="Pete Warden" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
            <div class="speaker_name_inkeynote"><a id="morik"></a>Pete Warden</div>
            <div class="speaker_aff_inkeynote">Google</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">TBA</div>

<!-- <button class="collapsible">Abstract -->
	<hr>
	<div class="abstract_context">
  TBA

	</div>


<br /> <br />

<div class="bio">
<button class="collapsible">Bio

<!-- <span class="bio_title">  </span> -->
<hr>
<div class="bio_context">
	Pete Warden is technical lead on the TensorFlow Micro team at Google, and was previously CTO at Jetpac, acquired by Google in 2014. 
</div>
</button>

<div class="tocollapse">
  TBA

  </div>
</div>

<br /><br /><br />
<div>
<div style="width:20%; float:left">
<img src="../assets/img/PaulWhatmough.jpg" alt="Paul Whatmough" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
      <div class="speaker_name_inkeynote"><a id="paul"></a>Paul Whatmough (Online)
			</div>
            <div class="speaker_aff_inkeynote">Arm ML Research Lab and Harvard University</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">Algorithm-Hardware Co-Design for Energy-Efficient Neural Network Inference</div>

	<hr>
	<div class="abstract_context">
    Machine learning has had a huge impact on consumer electronics devices, including IoT, mobile and automotive.  However, all these compute platforms are battery powered, which makes it challenging to use state-of-the-art machine learning models which typically demand an enormous number of arithmetic operations and a large memory footprint.

    <br /><br />
    In this talk, we will explore techniques for designing neural networks for energy-efficient inference on resource constrained devices.  In particular, we will emphasize the co-design of model and hardware, as a key approach to achieving state-of-the-art performance for real-time, energy-constrained inference applications on microcontrollers and mobile chips.
	</div>



<br /><br />
<div class="bio">
	<span class="bio_title"> Bio </span>
	<hr>
	<div class="bio_context">
    Paul Whatmough received the Doctorate degree from University College London, UK.
    He was previously with Philips, NXP, Arm, and Harvard, working in the areas of ML, DSP, wireless, accelerators, and circuits.
    Currently, he leads research at Arm ML Research Lab Boston, and is an Associate at Harvard.
	</div>
</div>
</div>

<div>

<br /> <br /> <br />
        <div style="width:20%; float:left">
			<img src="../assets/img/rikard.jpg" alt="Rikard König" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
            <div class="speaker_name_inkeynote"><a id="rikard"></a>Rikard König</div>
            <div class="speaker_aff_inkeynote">Ekkono Solutions</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">Edge Machine Learning in Practice</div>

<!-- <button class="collapsible">Abstract -->
	<hr>
	<div class="abstract_context">
  This talk will focus on challenges and opportunities when applying machine learning on edge devices. More specifically the talk will follow the journey and experiences from founding a company based on a research prototype, refining it to a real product and applying it to real world edge machine learning problems.
  <br /><br />
  The talk will draw upon experiences from numerous IoT projects performed during the last two years. Opportunities and challenges will be discussed in relation to implementation and algorithmic related requirements. A specific focus will be on incremental learning techniques since these has shown to be well suited for edge analytics.



	</div>


<br /> <br />

<div class="bio">
	<span class="bio_title"> Bio </span>
	<hr>

<!-- <span class="bio_title">  </span> -->
<div class="bio_context">
Rikard König, PhD, is co-founder and CTO at Ekkono Solutions and Senior Lecturer at the University of Borås, Sweden. At the University of Borås he is a member of CSL@BS, a research group of ten researchers specializing in machine learning and high-performance computing. The focus of his research is design of new or enhanced machine learning algorithms.
<br /> <br />
In December 2016, he co-founded Ekkono Solutions together we three other partners, based on the outcome of his research. Ekkono provides a resource efficient solution that can run most applicable machine learning techniques on small platforms, i.e. an edge computing platform for connected things. Today the company have grown to 17 employees and targets large industrial companies and have customers such as Siemens, Volvo, ABB and Alfa Laval.

</div>

</div>




<script>
	var coll = document.getElementsByClassName("collapsible");
	var i;

	for (i = 0; i < coll.length; i++) {
	  coll[i].addEventListener("click", function() {
	    this.classList.toggle("active");
	    var content = this.nextElementSibling;
	    if (content.style.maxHeight){
	      content.style.maxHeight = null;
	    } else {
	      content.style.maxHeight = content.scrollHeight + "px";
	    }
	  });
	}
</script>
