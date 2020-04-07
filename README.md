<p>Detector</p>
<div><nav class="navbar navbar-expand-md bg-dark navbar-dark fixed-top"><a class="navbar-brand" href="#detector">COVID-19 Detector</a> <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar"> </button>
<div id="collapsibleNavbar" class="collapse navbar-collapse">
<ul class="navbar-nav">
<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
<li class="nav-item"><a class="nav-link" href="#symptoms">Symptoms</a></li>
<li class="nav-item"><a class="nav-link" href="#precautions">Precautions</a></li>
<li class="nav-item"><a class="nav-link" href="#hospitals">Nearby Hospitals</a></li>
</ul>
</div>
</nav><br />
<div class="container mt-3" style="padding-top: 70px; padding-bottom: 0px;">
<div id="myCarousel" class="carousel slide" data-ride="carousel">
<div class="carousel-inner">
<div class="carousel-item active"><img src="https://i.imgur.com/qGxwlos.jpg" alt="" width="1100" height="600" /><img src="https://i.imgur.com/4oYBM9A.jpg" alt="" width="1100" height="600" /></div>
<div class="carousel-item"><img src="https://i.imgur.com/rIk63Bx.jpg" alt="symptoms of corona" width="1100" height="600" /></div>
</div>
<!-- Left and right controls --></div>
</div>
<div id="about" class="container" style="padding-top: 70px; padding-bottom: 0px;">
<h1>COVID-19</h1>
<p style="text-align: justify;">Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Coronaviruses are named for their appearance: Under the microscope, the viruses look like they are covered with pointed structures that surround them like a corona, or crown.</p>
<p style="text-align: justify;">There are many different kinds of coronaviruses. Some of them can cause colds or other mild respiratory (nose, throat, lung) illnesses. Other coronaviruses can cause more serious diseases, including severe acute respiratory syndrome (SARS) and Middle East respiratory syndrome (MERS).</p>
<p style="text-align: justify;">Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment. Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.</p>
<p style="text-align: justify;">The best way to prevent and slow down transmission is be well informed about the COVID-19 virus, the disease it causes and how it spreads. Protect yourself and others from infection by washing your hands or using an alcohol based rub frequently and not touching your face.</p>
<p style="text-align: justify;">The COVID-19 virus spreads primarily through droplets of saliva or discharge from the nose when an infected person coughs or sneezes, so it&rsquo;s important that you also practice respiratory etiquette (for example, by coughing into a flexed elbow).</p>
<p style="text-align: justify;">At this time, there are no specific vaccines or treatments for COVID-19. However, there are many ongoing clinical trials evaluating potential treatments. World Health Organisation(WHO) will provide updated information as soon as clinical findings become available.</p>
</div>
<div id="symptoms" class="container" style="padding-top: 70px; padding-bottom: 0px;">
<h2>Symptoms</h2>
<!--<p><b> Explain about the symptoms in covid patients here. List out the symptoms that we have used in out model to predict the covid. and write about symptoms that are not clear like conjuctivitis</b></p>-->
<p style="text-align: justify;">The COVID-19 virus affects different people in different ways. COVID-19 is a respiratory disease and most infected people will develop mild to moderate symptoms and recover without requiring special treatment.People who have underlying medical conditions and those over 60 years old have a higher risk of developing severe disease and death.</p>
Common symptoms include:
<ul>
<li>fever</li>
<li>tiredness</li>
<li>dry cough.</li>
</ul>
Other symptoms include:
<ul>
<li>shortness of breath</li>
<li>aches and pains</li>
<li>sore throat</li>
<li>and very few people will report diarrhoea, nausea or a runny nose.</li>
</ul>
<p style="text-align: justify;">The most common symptoms of COVID-19 are fever, tiredness, and dry cough. Some patients may have aches and pains, nasal congestion, runny nose, sore throat or diarrhea. These symptoms are usually mild and begin gradually. Some people become infected but don&rsquo;t develop any symptoms and don't feel unwell. Most people (about 80%) recover from the disease without needing special treatment. Around 1 out of every 6 people who gets COVID-19 becomes seriously ill and develops difficulty breathing. Older people, and those with underlying medical problems like high blood pressure, heart problems or diabetes, are more likely to develop serious illness. People with fever, cough and difficulty breathing should seek medical attention.</p>
</div>
<div id="detector" class="container" style="padding-top: 70px; padding-bottom: 0px;">
<h4>COVID-19 Detection based on symptoms</h4>
<p style="text-align: justify;">A self-diagnosis COVID-19 detection model to help you self diagnose your symptoms. This self-diagnosis is NOT a substitute for professional medical advice, diagnosis, or treatment. Always consult a medical professional for serious symptoms or emergencies.<br /> If you believe you have been exposed to COVID-19 and develop symptoms like fever, cough and difficulty of breathing, call your doctor!</p>
<!-- Button to Open the Modal 
  <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#myModal">
    Begin self-diagnosis
  </button>--></div>
<!-- The Modal 
  <div class="modal fade" id="myModal">
    <div class="modal-dialog">
      <div class="modal-content"> -->
<div class="container"><button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#demo">Begin Self Diagnosis</button></div>
<div class="container"><img src="https://i.pinimg.com/750x/25/5e/97/255e97d73f785ad4504f129171f6136e.jpg" alt="" /></div>
<div id="risk_analysis" class="container-fluid" style="padding-top: 70px; padding-bottom: 0px;">
<div class="container">
<p>&nbsp;</p>
<h4>Risk Assessment for COVID-19</h4>
<p style="text-align: justify;">Health-care provider (HCP) guidance outlines risk categories to determine work exclusion and monitoring procedures. After identifying risk category in the HCP guidance read the guidelines mentioned to determine quarantine measures and further use the self diagnosis (COVID-19 Detector) feature to predict your symptoms for the COVID-19.</p>
<!-- Trigger the modal with a button --> <!--   <button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#risk">Start Risk Analysis</button> --> <button class="btn btn-primary" type="button" data-toggle="modal" data-target="#risk">Start Risk Analysis</button> <!-- Modal -->
<div id="risk" class="modal fade">
<div class="modal-dialog"><!-- Modal content-->
<div class="modal-content">
<div class="modal-header">
<h4 class="modal-title">Question 1</h4>
<button class="close" type="button" data-dismiss="modal">&times;</button></div>
<div class="modal-body">
<p>Did you travel from China?</p>
<button class="btn btn-info" type="button" data-toggle="modal" data-target="#risk2a" data-dismiss="modal"> Yes</button> <button class="btn btn-info" type="button" data-toggle="modal" data-target="#risk2b" data-dismiss="modal"> No</button></div>
</div>
</div>
</div>
</div>
</div>
<div id="precautions" class="container" style="padding-top: 70px; padding-bottom: 0px;">
<h2>Precautions</h2>
<!--<p><b>Write about the effects of corona age wise its fatality and measure to prevent the corona and if already symptoms seen what precautions to be adopted to keep others safe and how to stay in isolation, hygienes etc etc </b> In this example, the navigation bar is hidden on small screens and replaced by a button in the top right corner (try to re-size this window).</p>
  -->
<p style="text-align: justify;">To help lessen the spread of the COVID-19, the disease it causes, here are important steps that can help protect you, your family and others. The following guideline is provided:</p>
<h4>Avoid close contact with others.</h4>
<p style="text-align: justify;">It&rsquo;s important to understand that the new coronavirus spreads mainly from person to person. If an infected person coughs or sneezes, their droplets can infect people nearby. That&rsquo;s why it&rsquo;s important to avoid close contact with others. Understand that people (including children) may be infected with the new coronavirus and have only mild symptoms.</p>
<p style="text-align: justify;">Some measures you can take to avoid close contact with others include:</p>
<ul>
<li>Stay home as much as possible and reduce visitors.</li>
<li>Practice social and physical distancing:</li>
<ul>
<li>Stay at least six feet away from others in public places.</li>
<li>Call friends and family or visit by video.</li>
</ul>
<li>Ask your employer if it&rsquo;s possible to work from home.&lt;l/i&gt;</li>
<li>Avoid people who appear sick.</li>
<li>Go grocery shopping and run errands during off-peak times.</li>
</ul>
<p style="text-align: justify;">Healthy people do not need to wear a mask unless they are caring for someone diagnosed with, or being monitored for, COVID-19, or respiratory illness.</p>
<h4>Practice good hygiene wherever you are.</h4>
<p style="text-align: justify;">The new coronavirus can survive for hours or even days on some surfaces. Touching a contaminated surface and then touching your face is one of the ways to become infected.<br /> The virus is no longer detectable on plastic after 72 hours, and on stainless steel or cardboard after about 48 hours. With that in mind:</p>
<ul>
<li style="text-align: justify;">Wash your hands with soap and water frequently and thoroughly for at least 20 seconds, especially:</li>
<ul>
<li>After being in public places and touching door handles, shopping carts, elevator buttons, etc.</li>
<li>After using the bathroom</li>
<li>Before preparing food</li>
</ul>
<li>If soap and water are not available, use hand sanitizer with at least 60% alcohol.</li>
<li>Avoid touching your eyes, nose or mouth, especially with unwashed hands.</li>
<li>If you cough or sneeze, do so in the bend of your elbow. If you use a tissue, throw it away immediately.</li>
</ul>
<p style="text-align: justify;"><strong>If you are sick with COVID-19 or think you might have COVID-19, follow the steps below to care for yourself and to help protect other people in your home and community.</strong></p>
<p style="text-align: justify;"><u>Stay home except to get medical care</u></p>
<ul>
<li style="text-align: justify;">Stay home: Most people with COVID-19 have mild illness and are able to recover at home without medical care. Do not leave your home, except to get medical care. Do not visit public areas.</li>
<li style="text-align: justify;">Stay in touch with your doctor. Call before you get medical care. Be sure to get care if you have trouble breathing, or have any other emergency warning signs, or if you think it is an emergency.</li>
<li>Avoid public transportation: Avoid using public transportation, ride-sharing, or taxis.</li>
</ul>
<p style="text-align: justify;"><u>Separate yourself from other people in your home, this is known as home isolation</u></p>
<ul>
<li style="text-align: justify;">Stay away from others: As much as possible, you stay away from others. You should stay in a specific &ldquo;sick room&rdquo; if possible, and away from other people in your home. Use a separate bathroom, if available.</li>
</ul>
<p style="text-align: justify;"><u>Call ahead before visiting your doctor</u></p>
<ul>
<li>Call ahead: Many medical visits for routine care are being postponed or done by phone</li>
<li style="text-align: justify;">If you have a medical appointment that cannot be postponed, call your doctor&rsquo;s office, and tell them you have or may have COVID-19. This will help the office protect themselves and other patients.</li>
</ul>
<p style="text-align: justify;"><u>If you are sick wear a cloth covering over your nose and mouth</u></p>
<ul>
<li>You should wear a cloth face covering, over your nose and mouth if you must be around other people even at home.</li>
</ul>
<p style="text-align: justify;"><u>Cover your coughs and sneezes</u></p>
<ol>
<li>Cover: Cover your mouth and nose with a tissue when you cough or sneeze.</li>
<li>Dispose: Throw used tissues in a lined trash can.</li>
<li style="text-align: justify;">Wash hands: Immediately wash your hands with soap and water for at least 20 seconds. If soap and water are not available, clean your hands with an alcohol-based hand sanitizer that contains at least 60% alcohol.</li>
</ol>
<p style="text-align: justify;"><u>Clean your hands often</u></p>
<ul>
<li style="text-align: justify;">Wash hands: Wash your hands often with soap and water for at least 20 seconds. This is especially important after blowing your nose, coughing, or sneezing; going to the bathroom; and before eating or preparing food.</li>
<li style="text-align: justify;">Hand sanitizer: If soap and water are not available, use an alcohol-based hand sanitizer with at least 60% alcohol, covering all surfaces of your hands and rubbing them together until they feel dry.</li>
<li style="text-align: justify;">Soap and water: Soap and water are the best option, especially if hands are visibly dirty.</li>
<li>Avoid touching: Avoid touching your eyes, nose, and mouth with unwashed hands.</li>
</ul>
<p style="text-align: justify;"><u>Avoid sharing personal household items</u></p>
<ul>
<li>Do not share: Do not share dishes, drinking glasses, cups, eating utensils, towels, or bedding with other people in your home.</li>
<li>Wash thoroughly after use: After using these items, wash them thoroughly with soap and water or put in the dishwasher.</li>
</ul>
<p style="text-align: justify;"><u>Clean all &ldquo;high-touch&rdquo; surfaces everyday</u></p>
<ul>
<li style="text-align: justify;">Clean high-touch surfaces in your isolation area (&ldquo;sick room&rdquo; and bathroom) every day; let a caregiver clean and disinfect high-touch surfaces in other areas of the home. <br />High-touch surfaces include phones, remote controls, counters, tabletops, doorknobs, bathroom fixtures, toilets, keyboards, tablets, and bedside tables.</li>
</ul>
<p style="text-align: justify;"><u>Monitor your symptoms</u></p>
<ul>
<ul>
<li style="text-align: justify;">Common symptoms of COVID-19 include fever and cough. Trouble breathing is a more serious symptom that means you should get medical attention.</li>
<li>If you are having trouble breathing, seek medical attention, but call first and tell them your symptoms. They will tell you what to do.</li>
<li style="text-align: justify;">Wear a cloth face covering (covers your nose and mouth):</li>
</ul>
</ul>
<p style="text-align: justify;">Put on the cloth face covering when you leave your house or when around other people. You don&rsquo;t need to wear the cloth face covering if you are alone. If you can&rsquo;t put on a cloth face covering (because of trouble breathing for example), cover your coughs and sneezes in some other way. Try to stay at least 6 feet away from other people. This will help protect the people around you.</p>
<ul>
<li>Follow care instructions from your healthcare provider and local health department</li>
</ul>
</div>
<div id="hospitals" class="container" style="padding-top: 70px; padding-bottom: 0px;">
<h2>Nearby Hospitals</h2>
<p>Below are listed the hospitals where you may get tested for covid-19 in Nepal</p>
<table class="table table-dark table-hover">
<thead>
<tr>
<th>Hosital Name</th>
<th>Open Hours</th>
<th>Contact</th>
</tr>
</thead>
<tbody>
<tr>
<td>Sukraraj Tropical And Infectious Disease Hospital</td>
<td>8 AM - 3 PM<br /> Sunday - Friday</td>
<td>01-4253395 , 01-4253396</td>
</tr>
<tr>
<td>Patan Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>01-5522295</td>
</tr>
<tr>
<td>Nepal APF Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>01-4315224</td>
</tr>
<tr>
<td>Bir Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>01-4221119</td>
</tr>
<tr>
<td>National Ayurveda Research and Training Center</td>
<td>10 AM - 3 PM<br /> Sunday - Friday</td>
<td>01-4334973</td>
</tr>
<tr>
<td>Birendra Sainik Hospital</td>
<td>8 AM - 5 PM<br /> Sunday - Friday</td>
<td>01-4271940</td>
</tr>
<tr>
<td>Mechi Zonal Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>023-520172</td>
</tr>
<tr>
<td>Udayapur District Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>035-420187</td>
</tr>
<tr>
<td>Janakpur Zonal Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>041-520133 , 041-520033</td>
</tr>
<tr>
<td>Bhaktapur Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>01-6610798</td>
</tr>
<tr>
<td>Sindhuli Hospital</td>
<td>6 AM &ndash; 9 PM<br /> Sunday - Saturday</td>
<td>047-520973</td>
</tr>
<tr>
<td>Dhaulagiri Zonal Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>9851176425 , 068-520188</td>
</tr>
<tr>
<td>Gorkha District Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>064-420208</td>
</tr>
<tr>
<td>Lumbini Zonal Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>071-541400</td>
</tr>
<tr>
<td>Tamghas Hospital</td>
<td>10 AM - 4 PM<br /> Sunday - Friday</td>
<td>079-520188</td>
</tr>
<tr>
<td>Surkhet District Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>083-525417</td>
</tr>
<tr>
<td>Dailekh District Hospital</td>
<td>8 AM - 8 PM<br /> Sunday - Saturday</td>
<td>089-410185</td>
</tr>
<tr>
<td>Seti Zonal Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>9841943586</td>
</tr>
<tr>
<td>Mahakalli Hospital</td>
<td>24 hours<br /> Sunday - Saturday</td>
<td>9843247009 , 099-521111</td>
</tr>
</tbody>
</table>
</div>
<!-- Footer --><footer class="page-footer font-small special-color-dark pt-4"><!-- Footer Elements -->
<div class="container-fluid p-3 my-3 bg-dark text-white"><!-- Social buttons --> <!-- Social buttons --></div>
<!-- Footer Elements --> <!-- Copyright -->
<div class="footer-copyright text-center py-3">&copy; 2020 Copyright: <a href="#"> ku-undergrads</a></div>
<!-- Copyright --></footer><!-- Footer --></div>
