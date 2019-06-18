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
			<img src="../assets/img/KatharinaMorik.png" alt="Katharina Morik" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
            <div class="speaker_name_inkeynote"><a id="morik"></a>Katharina Morik</div>
            <div class="speaker_aff_inkeynote">TU Dortmund University</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">Machine Learning for Sustainability</div>

<!-- <button class="collapsible">Abstract -->
	<hr>
	<div class="abstract_context">
  In September 2015, the general assembly of the United Nations passed
  17 goals for sustainability development that are to be reached until
  2030. This is an extension of the millennium development goals
  declaration from 2000. Since then, data analysis has contributed in
  several ways to sustainability, particularly in earth and climate
  science, in sustainable industrial production, and resource-efficient
  transportation.
<br /><br />
  This talk will give a short overview of the data-driven approaches and then present some approaches in more detail.
  Illustrating earth science, a novel method for gap filling in satellite images is presented.
  Sustainability for industrial production is presented with an example in steel production.
  The general view of resource-efficient computation is exemplified by Integer Markov Random Fields.
  Although there are already many approaches, a lot of work still needs to be done for lifting the full potential of machine learning for sustainability development.

	</div>


<br /> <br />

<div class="bio">
<button class="collapsible">Bio

<!-- <span class="bio_title">  </span> -->
<hr>
<div class="bio_context">
  Katharina Morik received her doctorate from the University of Hamburg in 1981 and her habilitation from the TU Berlin in 1988. In 1991, she established the chair of Artificial Intelligence at the TU Dortmund. Currently, her research interest is in learning under resource restrictions, e.g., in astrophysics, industry 4.0, or mobility.
   <br /> <br />
  In 2011, she acquired the Collaborative Research Center SFB 876 "Providing Information by Resource-Constrained Data Analysis” and is its spokeswoman since then.
  She is a director of the Competence Center for Machine Learning Rhein Ruhr (ML2R) and coordinator of the four German competence centers for machine learning.
</div>
</button>

<div class="tocollapse">
  The globally successful data analysis tool RapidMiner was developed at her lab.
  She is a leader of the working group "Technological Pioneers" of the German platform "Learning Systems and Data Science”.
  <br /> <br />
  She is the author of more than 200 publications in prestigious journals and conferences. Her focus on sustainability is seen, e.g., in the workshops SustainKDD at KDD 2011 and 2012 as well as the special issue in Data Mining and Knowledge Discovery 2012 and the coediting with Jörg Lässig and Kristian Kersting the book “Computational Sustainability” in 2016. She was a member of the editorial board of the journal Machine Learning and is currently one of the editors of the international journal Data Mining and Knowledge Discovery. She was a founding member, Program Chair and Vice Chair of the conference series IEEE International Conference on Data Mining (ICDM), Senior Chair of KDD, Area Chair of ICML, and Program Chair of ECML PKDD.
  <br /> <br />
  Prof. Morik has been a member of the Academy of Technical Sciences since 2015 and of the North Rhine-Westphalian Academy of Sciences and Arts since 2016.

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
