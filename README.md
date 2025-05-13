# cse408-project-1-text-classification-and-sentiment-analysis-solved
**TO GET THIS SOLUTION VISIT:** [CSE408 Project 1-Text Classification and Sentiment Analysis Solved](https://www.ankitcodinghub.com/product/cse408-project-1-text-classification-and-sentiment-analysis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92082&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE408 Project 1-Text Classification and Sentiment Analysis Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Programming language: Matlab (recommended and template codes provided), or other languages(without template codes)

</div>
</div>
<div class="layoutArea">
<div class="column">
Fourpeopleinateam.Listteammembersinyourreport,withnameandasuID. ImplementyourcodeunderCodefolder,andreaddatafromDatafolder(onefolderforkNNandonefor

sentiment analysis, or SA). WritetheprojectreportinfileP01_report.pdfandplaceattheprojectrootfolder.

Text Classification with Bag of Words and kNN

<ul>
<li>Input data under ../Data/kNN/training and ../Data/kNN/testing</li>
<li>Training directories pos and neg contain 90 text files each</li>
<li>Testing directories pos and neg contain 10 text files each</li>
<li>The directory name (pos, neg) corresponds to the true classification of each file</li>
<li>Grading will include running and inspecting the code and verifying output.
Vocabulary (lexicon) creation
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Implement function buildVoc.m

<ol>
<li>TemplatefilebuildVoc.m</li>
<li>Function template function voc = buildVoc(folder, voc, finvoc);</li>
<li>Inputs:
<ol>
<li>a &nbsp;folder is a folder path, which contains training data</li>
<li>b &nbsp;voc is a cell array to which the vocabulary is added so you can build a single lexicon for a set of
folders, the first time you call the fun voc is an empty cell array { }
</li>
<li>c &nbsp;finvoc is 0 the first time you call the function (e.g., with the pos data folder path) and 1
the second time (e.g., with the neg data folder path).
</li>
</ol>
</li>
<li>Output
<ol>
<li>a &nbsp;voc is a cell array which represents the vocabulary of the words shown in the data files, except the stop words (stop words list is embedded in the code template)</li>
<li>b &nbsp;when called with arg finvoc = 0, voc contains unique words, with frequency above a value of your choice.</li>
</ol>
</li>
<li>Implementyourcodeunder%PUTYOURIMPLEMENTATIONHEREtag;</li>
</ol>
a When you test the code check that the contents of the lexicon, i.e. array voc, do not have issues such as single characters or weird words that may cause performance issues. If needed add code to correct that.

</div>
</div>
<div class="layoutArea">
<div class="column">
6. UsefulMatlabfunctionsstrtok(),lower(),regexprep(),ismember(),any();

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
7. Includetheinstructionstogeneratevocandcut&amp;pastetheoutputintheprojectreport.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.2 Bag of Words feature extraction (10pt)

This function computes the BOW feature vector for any text file in the ../Data/kNN/* directory

<ol>
<li>Templatefilecse408_bow.m</li>
<li>Functiontemplatefunctionfeat_vec=cse408_bow(filepath,voc)</li>
<li>Inputs:
<ol>
<li>a &nbsp;filepath is a file path which contains one review (one .txt file)</li>
<li>b &nbsp;voc is the lexicon cell array from previous sub-section.</li>
</ol>
</li>
<li>Output:</li>
</ol>
a feat_vec is a one dimensional Matlab array, which represent the bag of words feature vector given the vocabulary voc

<ol start="5">
<li>Implementyourcodeunder%PUTYOURIMPLEMENTATIONHEREtag;</li>
<li>UsefulMatlabfunctionsstrtok(),lower(),regexprep(),ismember(),any();</li>
<li>Try out the implementation of function cse408_bow giving it a path to a text file, and voc (the lexicon).</li>
<li>Theoutputcanbecapturedandpastedintheprojectreport.Printonlythefeaturevaluesinasinglerow,
do not include the lexicon words as it is too long.
</li>
</ol>
1.3 k-NN Classification (15pt)

A set of reviews (training data) with their labels (pos, neg) is provided. The training data is under ../Data/kNN/training/{pos,neg}. The class labels (1 for positive, 0 for negative) should be stored in array train_label_set, and their feature vectors should be stored in array train_feat_set. The objective of the kNN classification is to use a distance metric to fin the k nearest neighbors of a test file (a review under ../Data/kNN/testing/{pos,neg}).

<ol>
<li>Templatefilecse408_knn.m

This function returns the label (positive or negative) predicted by the kNN algorithm for the feature

vector of a test file.
</li>
<li>Function template function pred_label = cse408_knn(test_feat, train_label_set, train_feat_set, k,
DstType)
</li>
<li>Inputarguments:
<ol>
<li>a &nbsp;test_feat is the feature vector of a test file (the size of test_feat is the same size as the lexicon)</li>
<li>b &nbsp;train_label_set is the set of labels for the training set (size is the number of training files)</li>
<li>c &nbsp;train_feat_set is the set of feature vectors for the training set (size is the size of lexicon X number of training files)</li>
<li>d &nbsp;k is the hyperparameter of kNN algorithm, i.e. the number of neighbors used</li>
<li>e &nbsp;DstType is the distance computation method, i.e. 1 for sum of squared distances (SSD) and 2
for angle between vectors and 3 for Number of words in common;
</li>
</ol>
</li>
<li>Output:</li>
</ol>
a pred_label is the predicted label of the testing file. 1 for positive review, 0 for negative review; 5. Implementyourcodeunder%PUTYOURIMPLEMENTATIONHEREtag;

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6. 7.

1.4

1.

2. 3.

2 2.1

1.

2. 3.

4. 5. 6.

2.2

1. 2. 3.

3

3.1

1. 2.

3. 4.

5.

</div>
<div class="column">
UsefulMatlabfunctionssort();

Try out function cse408_knn using appropriate arguments.

Test kNN implementation (10)

The test script for part one is provided in P01Part1_test.m. After your implementation, run P01Part1_test.m to debug and validate your code. It basically iteratively select one of the training review file as a validation file.

As you can see from the code, it uses the test data under ../Data/kNN/testing/{pos,neg}. Grader may run the implementation to verify it, so make sure it runs without problems

Text Sentiment Analysis (30pt) Implementation (15pt)

Implementabasicsentimentanalysismodule.Readinalexicon,inwhicheachwordhasasentimentscore (file wordWithStrenght in SA directory). Iterate through each review file and sum up the sentiment scores for each word that exists in the sentiment strength lexicon;

TemplatefilesentimentAnalysis.m

Input: a file path filepath, which contains one review (one .txt file) and a word with sentiment strength

file wordWithStrength.txt under ../Data/SA folder. Output:onesentimentscore. Implementyourcodeunder%PUTYOURIMPLEMENTATIONHEREtag; UsefulMatlabfunctionsstrtok(),lower(),regexprep(),containers.Map();

Test your implementation (15pt) Afteryourimplementation,runP01Part2test.mtodebugandvalidateyourcode. Reportontheaccuracyoftheperformanceofyourcode. Gradermayruntheimplementationtoverifyit,somakesureitrunswithoutproblems

Report Requirements (30pt)

Results presentation and analysis or discussion (20pt)

You may use the report template provided as guideline.

Make sure to explain where the algorithms worked and where they didn’t and why. You are encouraged to use both text and plots/graphs to explain your observations.

AnalyzeHyperparameterKintheKNNpart,whichKyouempiricallyobservedthatcouldachievethebest performance? You may draw a graph of performance vs. K.

Among the three distance metrics (sum of squared distances (SSD), and the angle between vectors and Number of words in common), which one intuitively makes more sense for classifying positive and negative review? Which one you empirically observed it to achieve the best performance?

For Text Sentiment Analysis task (Part II), which review in our dataset has the highest positive score but it is a negative review? And, which one has the lowest negative score, but it is a positive review?

Which set of words from these reviews confused your sentiment analysis system?

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3.2 Proposed improvements

There are many ways to improve either Knn and/or SentimentAnalysis, select one incremental approach and pursue it as far as time allows. For example: describe it in detail, implement it, test it, and compare with previous results. Points will be awarded according to the amount of work. Possible areas for improvement will be discussed in class. Document your approach and results in an Appendix of the report.

Matlab tips

Reading text from files:

First open the file using fun fopen:

&gt;&gt;Fd = fopen(‘..\P1\knn_training\reviews\neg\cv000_29416.txt’,’r’); Then read 10 lines (for knn exercise)

ns = ”;

for i = 1:10

ns = strcat(ns, fgetl(fd));

end

% the code above initializes the string to an empty string, then concatenates to it one line at a time using fun strcat. Each line is read using fun fgetl.

In order to remove punctuation marks (multiple spaces, etc.) you can use fun replace, for example replacing ‘.’ for ‘’; effectively deleting the character:

&gt;&gt; st

st =

they get into an accident .one of the guys dies , but his girlfriend continues to see him in her life , and has nightmares .

&gt;&gt; replace(st,’.’,”)

ans =

they get into an accident one of the guys dies , but his girlfriend continues to see him in her life , and has nightmares

You can replace multiple substrings at once if you use a cell array for the old string to replace:

&gt;&gt; replace(st,{‘,’,’.’,’;’},”)

nst = ‘they get into an accident one of the guys dies but his girlfriend continues to see him in her life and has nightmares’

to extract words from a string use fun strtok: &gt;&gt; [token remain] = strtok(nst)

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
token = they remain =

get into an accident one of the guys dies but his girlfriend continues to see him in her life and has nightmares

Use the help functions (top right search input, or select – right click on highlighted text in any view, then pick ‘help on selection’) for more information.

Other functions to try out:

lower(), regexprep(), containers.Map();

</div>
</div>
</div>
