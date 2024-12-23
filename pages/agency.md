---
layout: page
title: 
permalink: /agency/
---
<h3 id="perceived-agency">Perceived Agency</h3>
<hr><br>
We have developed a survey that measures perceived agency.  It can be used on any entity
(be it a robot, an AI, a person, an animal, or anything else). It has been tested on videos, images, and vignettes.

<p>Trafton, J. G., McCurry, J. M., Zish, K., & Frazier, C. R. (2024). <a href="/papers/PerceptionOfAgency.pdf" target="_blank">The Perception of Agency.</a> ACM Transactions on Human-Robot Interaction.</p>

<p>Trafton, J. G., Frazier, C. R., Zish, K., Bio, B. J., & McCurry, J. M. (2023, August). <a href="/papers/PAScaleReduction.pdf" target="_blank">The Perception of Agency: Scale Reduction and Construct Validity.</a> In 2023 32nd IEEE International Conference on Robot and Human Interactive Communication (RO-MAN) (pp. 936-942). IEEE.</p>

There are four versions:
<br>
<ol type="1">
  <li>The original PA survey (13 items) that was developed with Rasch; in order to get the
   best results, you will need to run calibration videos (below) and convert raw scores to
   latent scores. We believe this is the most sensitive measure of perceived agency
   available (though it does take a bit longer to run because of the calibration videos).
   Contact Greg if you have questions. R code to help with analysis will be posted
   eventually.</li>
  <li>The original PA survey (13 items).  To use, just average all responses.  Very accurate for measuring
   perceived agency.</li>
  <li>A reduced PA survey (8 items).  PAScale reduction paper used Rasch scale reduction methods to
   reduce the items from 13 to 8.  To use, average all responses.  Very accurate for measuring
   perceived agency.</li>
  <li>The quick and reduced PA survey (5 items). PAScale reduction paper used Rasch scale
   reduction methods to reduce the scale from 13 to 8 to 5. To use, average all responses.
   Very accurate for measuring perceived agency. We get excellent results using this
   reduced 5 scale version (see <a href="/papers/PAScaleReduction.pdf" target="_blank">The Perception of Agency: Scale Reduction and Construct Validity</a>.)</li>
</ol>  
<h3>Scales</h3>
Which scale to use?

If you need the most accurate method for measuring perceived agency, we recommend using
the 13 item scale with calibration videos developed in <a href="/papers/PerceptionOfAgency.pdf" target="_blank">The Perception of Agency</a>. It does take a bit
longer to administer because of the calibration videos.

If you are running a study with multiple surveys and scales, we recommend using the 5 item
scale that was developed in <a href="/papers/PerceptionOfAgency.pdf" target="_blank">The Perception of Agency</a> and then reduced and validated in <a href="/papers/PAScaleReduction.pdf" target="_blank">The Perception of Agency: Scale Reduction and Construct Validity</a>.

<b>Question wording:</b> Please answer the following questions about the [robot/human/character] named [X] [+ thumbnail image of X] in the video. A 5-point scale was used: Strongly Disagree - Disagree - Neutral - Agree - Strongly Agree
<table>
  <tr>
    <th>Items</th>
    <th>13</th>
    <th>8</th>
    <th>5</th>
  </tr>
  <tr>
    <td>acts with purpose</td>
    <td>x</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>has goals</td>
    <td>x</td>
    <td>x</td>
    <td></td>
  </tr>  
  <tr>
    <td>can create new goals</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>  
  <tr>
    <td>can communicate with people</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>
  <tr>
    <td>treats others as if they had a mind</td>
    <td>x</td>
    <td></td>
    <td></td>
  </tr>  
  <tr>
    <td>wanted to perform these actions</td>
    <td>x</td>
    <td>x</td>
    <td></td>
  </tr>    
  <tr>
    <td>can show emotions to other people</td>
    <td>x</td>
    <td></td>
    <td></td>
  </tr>    
  <tr>
    <td>can change their behavior based on how people treat them</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>    
  <tr>
    <td>can adapt to different situations</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>    
  <tr>
    <td>would do well in other environments</td>
    <td>x</td>
    <td></td>
    <td></td>
  </tr>    
  <tr>
    <td>can perform many different types of tasks</td>
    <td>x</td>
    <td></td>
    <td></td>
  </tr>    
  <tr>
    <td>actor scenario</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>    
  <tr>
    <td>dinner scenario</td>
    <td>x</td>
    <td>x</td>
    <td></td>
  </tr>                       
</table>
For the two scenarios, a 5-point scale was used with bookends of 'terrible' on the left and 'great' on the right.
<p style="font-size:95%; padding-left: 20px;">actor scenario: <span style="font-size:90%">Imagine the robot/character/person [+ thumbnail image] was asked to be an actor in a local theater production. How well do you think they would do?</span></p>
<p style="font-size:95%; padding-left: 20px;">dinner scenario: <span style="font-size:90%">Imagine the robot/character/person [+ thumbnail image] was asked to host a dinner party for your friends next weekend. How well do you think they will do?</span></p>
<h3>Calibration Videos</h3>
<table>
  <tr>
    <th>Label</th>
    <th>Morphology</th>
    <th>Entity Actions</th>
  </tr>
  <tr>
    <td><a href="/videos/table1/service.mp4" target="_blank">Service</a></td>
    <td>Humanoid</td>
    <td>Helping a human find a sports jersey in a store</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/cheater.mp4" target="_blank">Cheating RPS</a></td>
    <td>Humanoid</td>
    <td>Human playing a game of rock paper scissors; robot cheats</td>
  </tr>  
  <tr>
    <td><a href="/videos/table1/feeder.mp4" target="_blank">Feeder</a></td>
    <td>Arm</td>
    <td>Picking up food with a fork and feeding a human</td>
  </tr>  
</table>
<h3>Videos (from Table 1)</h3>
<table>
  <tr>
    <th>Label</th>
    <th>Morphology</th>
    <th>Entity Actions</th>
  </tr>
  <tr>
    <td><a href="/videos/table1/industrial.mp4" target="_blank">Industrial</a></td>
    <td>Industrial arm</td>
    <td>Stacking and moving boxes</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/feeder.mp4" target="_blank">Feeder</a></td>
    <td>Arm</td>
    <td>Picking up food with a fork and feeding a human</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/soccer.mov" target="_blank">Soccer</a></td>
    <td>Humanoid</td>
    <td>Shooting soccer goals</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/bargaining1.mp4" target="_blank">Bargaining1</a></td>
    <td>Humanoid character</td>
    <td>Human bargaining with AI agent</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/cheater.mp4" target="_blank">Cheating RPS</a></td>
    <td>Humanoid</td>
    <td>Human playing a game of rock paper scissors; robot cheats</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/octavia_george.mp4" target="_blank">Robot Secrets Revealed</a></td>
    <td>Humanoid</td>
    <td>Humans test robots who then rebel</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/math.mp4" target="_blank">Teacher</a></td>
    <td>Human</td>
    <td>Algebra math teacher</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/palletizer.mp4" target="_blank">Palletizer</a></td>
    <td>Industrial arm</td>
    <td>Stacking and moving pallets</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/dishes.mp4" target="_blank">Dishes</a></td>
    <td>Arm</td>
    <td>Moving coffee cups into strainer</td>
  </tr>
   <tr>
    <td><a href="/videos/table1/hubo.mp4" target="_blank">Line</a></td>
    <td>Rolling humanoid</td>
    <td>Reading signs and cutting in line</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/firefighter.mp4" target="_blank">Firefighting</a></td>
    <td>Humanoid</td>
    <td>Receiving instructions from a human and putting out a fire</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/bargaining2.mp4" target="_blank">Bargaining2</a></td>
    <td>Humanoid character</td>
    <td>Human bargaining with AI agent</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/service.mp4" target="_blank">Service</a></td>
    <td>Humanoid</td>
    <td>Helping a human find a sports jersey in a store</td>
  </tr>
  <tr>
    <td><a href="/videos/table1/musician.mp4" target="_blank">Musician</a></td>
    <td>Human</td>
    <td>Musician playing 4 parts</td>
  </tr>  
</table>
<h3>Videos (from Table 5)</h3>
<table>
  <tr>
    <th>Label</th>
    <th>Morphology</th>
    <th>Entity Actions</th>
  </tr>
  <tr>
    <td><a href="/videos/table5/welding.mp4" target="_blank">Welding</a></td>
    <td>Industrial arm</td>
    <td>Welding metal</td>
  </tr>  
  <tr>
    <td><a href="/videos/table5/taichi.mp4" target="_blank">TaiChi</a></td>
    <td>Humanoid</td>
    <td>Balancing and movement</td>
  </tr>  
  <tr>
    <td><a href="/videos/table5/asimo.mp4" target="_blank">Pouring</a></td>
    <td>Humanoid</td>
    <td>Pushes cart, unscrews thermos, pours juice and gives it to human</td>
  </tr>  
    <tr>
    <td><a href="/videos/table5/secrets.mp4" target="_blank">Robot Secrets Revealed '09</a></td>
    <td>Humanoid</td>
    <td>Magician tricking robot</td>
  </tr>  
  <tr>
    <td><a href="/videos/table5/bargaining3.mp4" target="_blank">Bargaining3</a></td>
    <td>Humanoid character</td>
    <td>Human bargaining with AI agent</td>
  </tr>  
    <tr>
    <td><a href="/videos/table5/closeted.mp4" target="_blank">Punished</a></td>
    <td>Humanoid</td>
    <td>Robot put in closet unwillingly</td>
  </tr>  
  <tr>
    <td><a href="/videos/table5/professor.mp4" target="_blank">Professor</a></td>
    <td>Human</td>
    <td>Teaching computer science</td>
  </tr>  
</table>
<hr><hr><br>
<h3 id="perceived-danger">Perceived Danger</h3>
<hr><br>
<p>We have developed a survey that measures Perceived Danger in robots... etc...</p>
