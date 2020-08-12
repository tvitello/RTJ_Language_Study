 ## RTJ_Language_Study
 ## Final Project for DS5001, a UVA Course in the MSDS Curriculum
 ## Project submitted for DS5001, University of Virginia
 ## Summer 2020, MSDS Program
 ## Travis Vitello
 ## tjv9qh@virginia.edu

<b> NOTE: It looks like Github doesn't render strings with "$" correctly and that plotly_express visualizations are not rendered; these issues do not exist in the code, which can be downloaded! </b>


This is an exploratory text analytics study focused on the discography of the hip-hop duo Run the Jewels.
 
Content includes two Jupyter Notebooks that perform all text acquisition, pre-processing, and processing steps as well as two .JPG files used in the notebooks (one of which is the basis for the WordCloud mask).
 
 Output is generated as .CSV files (both censored and uncensored versions) which is also included.
 
 From Raf Alvarado of UVA, I've included a salex_nrc.csv file which serves as the EmoLex dictionary used for sentiment analysis.
 
 Finally, I included my UVA project write-up which the code here supplements.

 Note that in the code itself and in the displayed output, there should be no adult language that is uncensored.
 
 However, given the nature of the lyrics used as the basis of the corpus in this study, there is adult language!
 
 User discretion is advised in that regard. Note that I wrote a censorship function that hopefully captures nearly all of the adult language; analytically, the code processes the uncensored language but displays only the censored versions (meaning I'm basically holding in memory two sets of data simultaneously)!
 
This can get resource intense, which is why the separate notebook is used (whereby the .CSV files generated by the first notebook get read in as input).  If the user wants to start with the second notebook, that's OK --- since all of the .CSV files are there.


 Note that this code can probably be simplified and cleaned up in some places, which I'll certainly consider during future studies!

 Cheers,
 
 Travis
