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
  <img src="../assets/img/morik.png" alt="Katharina Morik" style="width:100%; margin-bottom: 20px; padding-left: 0px">
</div>
<div>
<div class="speaker_name_inkeynote"><a id="morik"></a>Katharina Morik</div>
<div class="speaker_aff_inkeynote">TU Dortmund University</div>
</div>
</div>

<div style="clear:left;">
<!-- <div class="keynote_title">TITLE</div>

<!-- <button class="collapsible"> -->
<!-- <span class="bio_title"> Abstract </span>
	<hr>
	<div class="abstract_context">
	TBI -->
<!-- </button> -->
<!-- <div class="tocollapse"> -->

   <!-- <br />
  <br />

	<br /><br /> -->


  <!-- </div> -->

<!-- <button class="collapsible">Bio</button>
<div class="tocollapse">
<p> -->
<!-- <br />
<div class="bio">
<span class="bio_title"> Bio </span>
<hr>
<div class="bio_context">
TBA
</div>
</div> -->
<!-- </p>
</div> -->

<br /><br /><br />
<div>
<div style="width:20%; float:left">
  <img src="../assets/img/PaulWhatmough.jpg" alt="Paul Whatmough" style="width:100%; margin-bottom: 20px; padding-left: 0px">
</div>
<div>

<div class="speaker_name_inkeynote"><a id="paul"></a>Paul Whatmough
  			<!-- <span class="fa-stack fa-lg">
            <i class="fa fa-twitter fa-stack-1x fa-inverse" style="font-size:0.8em; color:#10872F"></i>
        	</span> -->
</div>
<div class="speaker_aff_inkeynote">Arm ML Research Lab and Harvard University</div>
</div>
<!-- </div> -->

<div style="clear:left;">
<div class="keynote_title">Algorithm-Hardware Co-Design for Energy-Efficient Neural Network Inference</div>

<span class="bio_title"> Abstract </span>
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
</div>
<div class="bio_context">
Paul Whatmough received the Doctorate degree from University College London, UK.
He was previously with Philips, NXP, Arm, and Harvard, working in the areas of ML, DSP, wireless, accelerators, and circuits.
Currently, he leads research at Arm ML Research Lab Boston, and is an Associate at Harvard.

</div>
<!-- </div>
</div> -->



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
