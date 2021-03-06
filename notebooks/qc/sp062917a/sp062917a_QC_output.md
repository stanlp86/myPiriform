
<a id='top'></a>
# Experiment: sp062917a


##### [The Basics](#The Basics)
##### [Segmentation](#Alignment)
- [Masks](#Mask)

##### [Activity Basics](#Activity)  
- [FOV SNR](#SNR)  
- [Events](#Events)
    - [Distribution of event magnitudes](#Distribution of event magnitudes)
    - [Distribution of event durations](#Distribution of event durations)
    - [Average number of events per cell ](#Average number of events per cell )
    - [Average event frequency](#Average event frequency)  
    
##### [Odor evoked activity](#Odor Evoked Activity)
- [Trial-averaged responses](#Trial-averaged responses)
  - [By odor](#By odor)
      - [excitatory](#excitatoryByOdor)
      - [inhibitory](#inhibitoryByOdor)
- [Cumulative number of trials with detected responses](#Cumulative number of trials with detected responses)
- [Fraction of cells responding to multiple odors](#Fraction of cells responding to multiple odors)
- [Fraction of responsive population by odor](#Fraction of responsive population by odor)
- [Lifetime Sparseness](#Lifetime Sparseness)

<a id='The Basics'></a>
# The Basics

<a id='Number of Trials'></a>
##### Number of Trials

- Awake: 10

##### Layer II
 - Total number of cells in Slice 0 FOV:   
     - excitatory: 234
     - inhibitory: 2
 - Total number of cells in Slice 1 FOV: 
     - excitatory: 200
     - inhibitory: 9
 - Total number of cells in Slice 2 FOV:  
     - excitatory: 129
     - inhibitory: 13
 
<br></br>   
##### Layer III

 - Total number of cells in Slice 3 FOV:
     - excitatory: 106
     - inhibitory: 12
 - Total number of cells in Slice 4 FOV: 
     - excitatory: 86
     - inhibitory: 12
 - Total number of cells in Slice 5 FOV:  
     - excitatory: 55
     - inhibitory: 7

<a id='Stimulus set'></a>
##### Stimulus set

- 22 odors (and 1 sham) presented pseudorandomly    

- **Inter-stimulus-interval**: 30 seconds  
- **Odor presentation**: 2 seconds
  
<br></br>
Odor 0: Blank
<br></br>

-|-|-|-  
:---|:---|:---|:---|:---|:---
1: y_decalactone <br></br>2: ethylhexyl_tiglate<br></br>3: undecanal<br></br>4: aniline<br></br>5: 2mthxy6prpn2ylprzine|6: 2-methylpyrazine<br></br>7: putrescence<br></br>8: 4METHYLTHIOBUTANOL<br></br>9: dicyclohxl_disulfide <br></br>10: 4-allylanisole<br></br>|11: benzyl_isothiocyanate<br></br>12: R-camphor<br></br> 13: trithioacetone<br></br>14: linalool<br></br>15: isothiocineole<br></br>16: lillial|17: tetrahydrothiophene <br></br>18: 3-phnlprpl_2-mthlpropnte<br></br>19: isoquinoline<br></br>20: indole<br></br>21: 235trimethylpyrazine<br></br>22: methyl-2-furoate

***

<a id='Alignment'></a>
# Segmentation
[back to top](#top)

<a id='Mask'></a>
### Mask overlays

##### Green channel

slice 0: Trial e1_006|slice 1: Trial e1_006|slice 2: Trial e1_006
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_0_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_1_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_2_green.png" />

slice 3: Trial e1_004|slice 4: Trial e1_004|slice 5: Trial e1_004
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_3_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_4_green.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_5_green.png" />

##### Red channel

slice 0: Trial e1_006|slice 1: Trial e1_006|slice 2: Trial e1_006
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_0_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_1_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_2_red.png" />

slice 3: Trial e1_004|slice 4: Trial e1_004|slice 5: Trial e1_004
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_3_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_4_red.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/Mask_slice_5_red.png" />

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

Layer II slice 0|Layer II slice 1|Layer II slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_2.png" />
50th percentile: 5.5|50th percentile: 5.3|50th percentile: 5.0

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/SNR_slice_5.png" />
50th percentile: 5.3|50th percentile: 5.2|50th percentile: 5.6

<a id='Events'></a>
## Events
[Back to Activity Basics](#Activity)

   - [Distribution of event magnitudes](#Distribution of event magnitudes)
   - [Distribution of event durations](#Distribution of event durations)
   - [Average number of events per cell ](#Average number of events per cell )
   - [Average event frequency](#Average event frequency)  

<a id='Distribution of event magnitudes'></a>
### Distribution of event magnitudes


Layer II slice 0|Layer II slice 1|Layer II slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_0.png" />  |<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_3.png" />  |<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/event_magnitudes_slice_5.png" />

<a id='Distribution of event durations'></a>
### Distribution of event durations  

Layer II slice 0|Layer II slice 1|Layer II slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/normed_event_duration_slice_5.png" />



<a id='Average number of events per cell'></a>
### Average number of events per cell 
slice 0|slice 1|slice 2|slice 3|slice 4|slice 5
:---:|:---:|:---:|:---:|:---:|:---:
77 | 58 | 40 | 48 | 44 | 54

<a id='Average event frequency'></a>
### Average event frequency


slice 0|slice 1|slice 2|slice 3|slice 4|slice 5
:---:|:---:|:---:|:---:|:---:|:---:
0.1 | 0.08 | 0.05 | 0.07 | 0.06 | 0.07


---


<a id='Odor Evoked Activity'></a>
# Odor-evoked activity 
[back to top](#top)


- [Trial-averaged responses](#Trial-averaged responses)
  - [By odor](#By odor)
      - [excitatory](#excitatoryByOdor)
      - [inhibitory](#inhibitoryByOdor)
- [Cumulative number of trials with detected responses](#Cumulative number of trials with detected responses)
- [Fraction of cells responding to multiple odors](#Fraction of cells responding to multiple odors)
- [Fraction of responsive population by odor](#Fraction of responsive population by odor)
- [Lifetime Sparseness](#Lifetime Sparseness)

<a id='Trial-averaged responses'></a>
<a id='By odor'></a>
<a id='excitatoryByOdor'></a>
### Trial-averaged responses
##### Excitatory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves0_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves1_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves2_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves3_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves4_exc.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves5_exc.png" />

<a id='inhibitoryByOdor'></a>
##### Inhibitory neurons
[Back to Odor Evoked Activity](#Odor Evoked Activity)

<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves0_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves1_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves2_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves3_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves4_inh.png" />
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/byOdor_trialAves5_inh.png" />

<a id='Cumulative number of trials with detected responses'></a>
### Cumulative number of trials with detected responses
[Back to Odor Evoked Activity](#Odor Evoked Activity) 
<br></br> 


Layer II slice 0|Layer II slice 1| Layer II slice 2 |Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:|:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_2.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/CumTrialsWithResponseByOdor_5.png" />




<a id='Fraction of responsive population by odor'></a>
### Fraction of population that responds to odors. Presented for each odor
[Back to Odor Evoked Activity](#Odor Evoked Activity)  
<br></br>  
-This is calculated on cells that respond to an odor on at least 50 percent of the trials. 

Layer II slice 0|Layer II slice 1| Layer II slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/response_density_slice_5.png" />

<a id='Fraction of cells responding to multiple odors'></a>
### Fraction of cells responding to multiple odors
[Back to Odor Evoked Activity](#Odor Evoked Activity)    
<br></br>  
-This is calculated on cells that respond to an odor on at least 50 percent of the trials. 

Layer II slice 0|Layer II slice 1|Layer II slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_2.png" />

Layer III slice 3|Layer III slice 4|Layer III slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/cells_across_odors_slice_5.png" />

<a id='Lifetime Sparseness'></a>
### Lifetime Sparseness
[Back to Odor Evoked Activity](#Odor Evoked Activity)  
<br></br>  

Layer II, slice 0|Layer II, slice 1|Layer II, slice 2
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_0.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_1.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_2.png" />

Layer III, slice 3|Layer III, slice 4|Layer III, slice 5
:---:|:---:|:---:
<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_3.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_4.png" />|<img src="https://raw.githubusercontent.com/stanlp86/myPiriform/master/notebooks/qc/sp062917a/LS_slice_5.png" />


```python
from IPython.core.display import HTML, display
import urllib2
display(HTML("<style>.container { width:75% !important; }</style>"))
HTML(urllib2.urlopen('http://bit.ly/1Bf5Hft').read())

```


<style>.container { width:75% !important; }</style>





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


