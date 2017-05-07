
<a id='top'></a>
# Experiment: 
<br></br>
sp042117a_e1_slice_0  
sp042117a_e1_slice_1  
sp042117a_e1_slice_2  
sp042117a_e1_slice_3  
sp042117a_e1_slice_4  
sp042117a_e1_slice_5  



#### Contents
[The Basics](#The Basics)  

<br/>
[Segmentation](#Alignment)
- [Masks](#Mask)

<br/>
[Activity Basics](#Activity)  
- [FOV SNR](#SNR)  
- [Events](#Events)
    - [Distribution of event magnitudes](#Distribution of event magnitudes)
    - [Distribution of event durations](#Distribution of event durations)
    - [Average number of events per cell ](#Average number of events per cell )
    - [Average event frequency](#Average event frequency)  
    
<br/>
[Odor evoked activity](#Odor Evoked Activity)
- [Trial-averaged responses](#Trial-averaged responses)
  - [By odor](#By odor)
      - [excitatory](#excitatoryByOdor)
      - [inhibitory](#inhibitoryByOdor)
  - [Class averages](#Class averages)
      - [excitatory](#excitatory)
      - [inhibitory](#inhibitory)
- [Cumulative number of trials with detected responses](#Cumulative number of trials with detected responses)
- [Fraction of cells responding to multiple odors](#Fraction of cells responding to multiple odors)
- [Fraction of responsive population by odor](#Fraction of responsive population by odor)
- [Lifetime Sparseness](#Lifetime Sparseness)




<a id='The Basics'></a>
# The Basics

<a id='Number of Trials'></a>
##### Number of Trials

- Awake: 14

##### Layer II
 - Total number of cells in Slice 0 FOV:   
     - excitatory: 162
     - inhibitory: 4
 - Total number of cells in Slice 1 FOV: 
     - excitatory: 171
     - inhibitory: 13
 - Total number of cells in Slice 2 FOV:  
     - excitatory: 159
     - inhibitory: 14
 
<br></br>   
##### Layer III

 - Total number of cells in Slice 3 FOV:
     - excitatory: 110
     - inhibitory: 10
 - Total number of cells in Slice 4 FOV: 
     - excitatory: 108
     - inhibitory: 9
 - Total number of cells in Slice 5 FOV:  
     - excitatory: 100
     - inhibitory: 12

<a id='Stimulus set'></a>
##### Stimulus set

- 23 odors presented pseudorandomly    

- **Inter-stimulus-interval**: 30 seconds  
- **Odor presentation**: 2 seconds
  
<br></br>
Odor 0: Blank
<br></br>

esters|aldehydes|ketones|acids  
:---|:---|:---|:---|:---|:---
1: ethylAcetate <br></br>2: propylAcetate<br></br>3: butylAcetate<br></br>4: pentylAcetate<br></br>5: hexylAcetate|6: propanal<br></br>7: butanal<br></br>8: pentanal<br></br>9: heptanal <br></br>10: octanal<br></br>|11: propanone<br></br>12: butanone<br></br> 13: pentanone<br></br>14: hexanone<br></br>15: heptanone<br></br>16: octanone|17: propanoicAcid <br></br>18: butanoicAcid<br></br>19: pentanoicAcid<br></br>20: hexanoicAcid<br></br>21: heptanoicAcid<br></br>22: octanoicAcid

***

<a id='Alignment'></a>
# Segmentation
[back to top](#top)

<a id='Mask'></a>
### Mask overlays

##### Green channel

slice 0: Trial e1_006|slice 1: Trial e1_006|slice 2: Trial e1_006
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_0_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_1_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_2_green.png" />

slice 3: Trial e1_004|slice 4: Trial e1_004|slice 5: Trial e1_004
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_3_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_4_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_5_green.png" />

##### Red channel

slice 0: Trial e1_006|slice 1: Trial e1_006|slice 2: Trial e1_006
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_0_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_1_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_2_red.png" />

slice 3: Trial e1_004|slice 4: Trial e1_004|slice 5: Trial e1_004
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_3_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_4_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/Mask_slice_5_red.png" />

___

<a id='Activity'></a>
# Activity Basics
[back to top](#top)

- [FOV SNR](#SNR)  
- [Events](#Events)
    - [Distribution of event magnitudes](#Distribution of event magnitudes)
    - [Distribution of event durations](#Distribution of event durations)
    - [Average number of events per cell ](#Average number of events per cell )
    - [Average event frequency](#Average event frequency)  

<a id='SNR'></a>
## SNR
[Back to Activity Basics](#Activity)

Layer II slice 0|Layer II slice 1|Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_2.png" />
50th percentile: 5.2|50th percentile: 5.2|50th percentile: 5.1

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/SNR_slice_5.png" />
50th percentile: 5.2|50th percentile: 5.2|50th percentile: 5.1

<a id='Events'></a>
## Events
[Back to Activity Basics](#Activity)

   - [Distribution of event magnitudes](#Distribution of event magnitudes)
   - [Distribution of event durations](#Distribution of event durations)
   - [Average number of events per cell ](#Average number of events per cell )
   - [Average event frequency](#Average event frequency)  

<a id='Distribution of event magnitudes'></a>
### Distribution of event magnitudes


Layer II slice 0|Layer II slice 1|Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_0.png" />  |<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_3.png" />  |<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/event_magnitudes_slice_5.png" />

<a id='Distribution of event durations'></a>
### Distribution of event durations  

Layer II slice 0|Layer II slice 1|Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/normed_event_duration_slice_5.png" />



<a id='Average number of events per cell'></a>
### Average number of events per cell 
slice 0|slice 1|slice 2|slice 3|slice 4|slice 5
:---:|:---:|:---:|:---:|:---:|:---:
67 | 64 | 63 | 66 | 65 | 66

<a id='Average event frequency'></a>
### Average event frequency


slice 0|slice 1|slice 2|slice 3|slice 4|slice 5
:---:|:---:|:---:|:---:|:---:|:---:
0.1 | 0.1 | 0.1 | 0.1 | 0.1 | 0.1


---


<a id='Odor Evoked Activity'></a>
# Odor-evoked activity 
[back to top](#top)


- [Trial-averaged responses](#Trial-averaged responses)
  - [By odor](#By odor)
      - [excitatory](#excitatoryByOdor)
      - [inhibitory](#inhibitoryByOdor)
  - [Class averages](#Class averages)
      - [excitatory](#excitatory)
      - [inhibitory](#inhibitory)
  
- [Fraction of cells responding to multiple odors](#Fraction of cells responding to multiple odors)
- [Fraction of responsive population by odor](#Fraction of responsive population by odor)
- [Lifetime Sparseness](#Lifetime Sparseness)

<a id='Trial-averaged responses'></a>
<a id='By odor'></a>
<a id='excitatoryByOdor'></a>
### Trial-averaged responses
##### Excitatory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves0_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves1_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves2_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves3_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves4_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves5_exc.png" />

<a id='inhibitoryByOdor'></a>
##### Inhibitory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves0_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves1_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves2_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves3_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves4_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/byOdor_trialAves5_inh.png" />

<a id='Class averages'></a>
<a id='excitatory'></a>
### Class averages
##### Excitatory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_0_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_1_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_2_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_3_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_4_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_5_exc.png" />

<a id='inhibitory'></a>
##### Inhibitory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_0_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_1_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_2_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_3_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_4_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/classAves_5_inh.png" />

<a id='Cumulative number of trials with detected responses'></a>
### Cumulative number of trials with detected responses
[Back to Odor Evoked Activity](#Odor Evoked Activity) 
<br></br> 


Layer II slice 0|Layer II slice 1| Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/CumTrialsWithResponseByOdor_5.png" />

<a id='Fraction of responsive population by odor'></a>
### Fraction of population that responds to odors. Presented for each odor
[Back to Odor Evoked Activity](#Odor Evoked Activity)  
<br></br>  
-This is calculated on cells that respond to an odor on at least 50 percent of the trials. 

Layer II slice 0|Layer II slice 1| Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/response_density_slice_5.png" />

<a id='Fraction of cells responding to multiple odors'></a>
### Fraction of cells responding to multiple odors
[Back to Odor Evoked Activity](#Odor Evoked Activity)    
<br></br>  
-This is calculated on cells that respond to an odor on at least 50 percent of the trials. 

Layer II slice 0|Layer II slice 1|Layer III slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/cells_across_odors_slice_5.png" />

<a id='Lifetime Sparseness'></a>
### Lifetime Sparseness
[Back to Odor Evoked Activity](#Odor Evoked Activity)  
<br></br>  

Layer II, slice 0|Layer II, slice 1|Layer III, slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_2.png" />

Layer III, slice 3|Layer III, slice 4|Layer III, slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp042117a/LS_slice_5.png" />


```python

from IPython.core.display import HTML
import urllib2
HTML(urllib2.urlopen('http://bit.ly/1Bf5Hft').read())
```




<style>

html {
  font-size: 62.5% !important; }
body {
  font-size: 1.5em !important; /* currently ems cause chrome bug misinterpreting rems on body element */
  line-height: 1.6 !important;
  font-weight: 400 !important;
  font-family: "Raleway", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif !important;
  color: #222 !important; }

div{ border-radius: 0px !important;  }
div.CodeMirror-sizer{ background: rgb(244, 244, 248) !important; }
div.input_area{ background: rgb(244, 244, 248) !important; }

div.out_prompt_overlay:hover{ background: rgb(244, 244, 248) !important; }
div.input_prompt:hover{ background: rgb(244, 244, 248) !important; }

h1, h2, h3, h4, h5, h6 {
  color: #333 !important;
  margin-top: 0 !important;
  margin-bottom: 2rem !important;
  font-weight: 300 !important; }
h1 { font-size: 4.0rem !important; line-height: 1.2 !important;  letter-spacing: -.1rem !important;}
h2 { font-size: 3.6rem !important; line-height: 1.25 !important; letter-spacing: -.1rem !important; }
h3 { font-size: 3.0rem !important; line-height: 1.3 !important;  letter-spacing: -.1rem !important; }
h4 { font-size: 2.4rem !important; line-height: 1.35 !important; letter-spacing: -.08rem !important; }
h5 { font-size: 1.8rem !important; line-height: 1.5 !important;  letter-spacing: -.05rem !important; }
h6 { font-size: 1.5rem !important; line-height: 1.6 !important;  letter-spacing: 0 !important; }

@media (min-width: 550px) {
  h1 { font-size: 5.0rem !important; }
  h2 { font-size: 4.2rem !important; }
  h3 { font-size: 3.6rem !important; }
  h4 { font-size: 3.0rem !important; }
  h5 { font-size: 2.4rem !important; }
  h6 { font-size: 1.5rem !important; }
}

p {
  margin-top: 0 !important; }
  
a {
  color: #1EAEDB !important; }
a:hover {
  color: #0FA0CE !important; }
  
code {
  padding: .2rem .5rem !important;
  margin: 0 .2rem !important;
  font-size: 90% !important;
  white-space: nowrap !important;
  background: #F1F1F1 !important;
  border: 1px solid #E1E1E1 !important;
  border-radius: 4px !important; }
pre > code {
  display: block !important;
  padding: 1rem 1.5rem !important;
  white-space: pre !important; }
  
button{ border-radius: 0px !important; }
.navbar-inner{ background-image: none !important;  }
select, textarea{ border-radius: 0px !important; }

</style>


