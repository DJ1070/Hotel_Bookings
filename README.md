# Hotel Bookings

<img src = "https://www.urlaubstracker.de/wp-content/uploads/2016/10/porto_sonnenuntergang.jpg">

<h2>Project Background & Purpose</h2>
<p>This project served 2 purposes:</p>
<ol>
    <li>The data exploration shall reveal the travel, booking, cancelling and other types of behaviour of hotel guests.
        <ul>
            <li>Who travels with whom? </li>
            <li>Do families differ in booking and traveling from adults without kids? If so, how? </li>
            <li>Which budgets are available for overnight stays? </li>
            <li>Which similarities and differences show up between guests of the city and the resort hotel?</li>
            <li>And many other questions.</li>
        </ul>
        <br>These questions have to be explored in an open and unbiased way, because human (inter)action is what interests me most. That's why I want to find out which valuable indications about human behaviour and traveling habits are embedded in plain data as this hotel reservation data - beyond the usual data exploration.</li>
    <br>
<li>Machine Learning: Solving a Classification Problem<br>
By means of Machine Learning it was to determine if a prediction can be made with a high probability whether guests set forth on a journey or whether they cancel the planned hotel overnight stays.</li>
</ol>


<h2>The Dataset</h2>
<p>The dataset comes from 2 Portugese hotels, a city and a resort hotel. It contains overnighters from the years 2015, 2016, and 2017 as well as cancelled bookings.</p>
<p>The data is imbalanced in many ways, starting with twice as much data for the city hotel compared to the resort hotel. The hotels are more popular among adults traveling without kids. The vast majority of the guests stems from Portugal even though the total guest variety is high: People from as much as 178 different countries booked their stays in just these two hotels! And of course there's some data that doesn't make any sense, e. g. bookings for 0 adults and some children (including babies) or even 0 kids.</p>


<h2>My Approach</h2>
<p>I approached the dataset from a marketing perspective. I have been working 30+ years in marketing and have spent the last 20+ years studying user and consumer behavior. 
    Hence I did defined typical KPIs - but moreover I looked beyond them. The data contains hints to innumerous aspects of human needs and behavior patterns. There are many questions data cannot answer, but it points to all that needs to be investigated further to truly understand how to serve customers needs better. And that should always be the core of strategic marketing.</p>


<h2>Machine Learning</h2>
<p>Following are the various strategies and methods I used to predict the cancellation rate with a reasonable accuracy and Kappa score. Contrary to other data scientists working on this dataset I did not try to reach > 99% accuracy due to the danger of overfitting. </p>
<h4>My Strategies:</h4>
    <ul>
        <li>Standardization</li>
        <li>Normalization</li>
        <li>Dummification</li>
        <li>Correlation Matrix</li>
        <li>Feature selection</li>
        <li>Outlier deletion</li>
        <li>Splitting hotel data</li>
        <li>Even different random states in train-test-split</li>
        <li>And finally: <a href = "https://medium.com/@breya.heysoftware/synthetic-minority-over-sampling-technique-smote-from-scratch-e1167f788434">SMOTE</a>.</li>
    </ul>
<h4>The Classification Methods I Used:</h4>
    <ul>
        <li>Logistic Regression</li>
        <li>Decision Tree</li>
        <li>K-Fold Decision Tree</li>
        <li>KNN</li>
        <li>Random Forest</li>
        <li>Ada Boost Classifier</li>
        <li>Gradient Boosting Classifier</li>
        <li>XgBoost Classifier</li>
        <li>Cat Boost Classifier</li>
        <li>Extra Trees Classifier</li>
        <li>LGBM Classifier</li>
        <li>Voting Classifier.</li>
    </ul>


<h2>Results</h2>
<ol>
<li>There are too many results and insights from just a little bit of exploration (there was no time for more). Please take a look at my short <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Presentation/Hotel_Bookings_Presentation_Diana_Jaffe.pdf">presentation</a> and for more in the <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Hotel_Exploration.ipynb">exploration file "Hotel_Exploration.ipynb"</a>, if you will. </li>
<li>The best machine learning results are contained in the file <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Hotel_Cancellation_Prediction.ipynb">"Hotel_Cancellation_Prediction.ipynb"</a>.<br><br>
    <b>SPOILER ALERT!</b><br><br>
    <b>Random Forest Classifier delivered the best result with</b><br> 
    <b>Accuracy = 0.932411</b><br>
    <b>Kappa = 0.864827</b><br><br>
    As mentioned above: I tried to not overfit my models.</li><br>
<li>You can find my other / earlier machine learning attempts on this datasets in the folder <a href = "https://github.com/DJ1070/Hotel_Bookings/tree/main/Machine_Learning">Machine_Learning</a> (but you really don't have to).</li>
</ol>



<p>There are too many results and insights from just a little bit of exploration (there was no time for more). Please take a look at my short <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Presentation/Hotel_Bookings_Presentation_Diana_Jaffe.pdf">presentation</a> and for more in the <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Hotel_Exploration.ipynb">exploration file "Hotel_Exploration.ipynb"</a>, if you will. </p>
<p>The best machine learning results are contained in the file <a href = "https://github.com/DJ1070/Hotel_Bookings/blob/main/Hotel_Cancellation_Prediction.ipynb">"Hotel_Cancellation_Prediction.ipynb"</a>.</p>
<p>SPOILER ALERT!</p>
<p>Random Forest Classifier delivered the best result with<br> 
    Accuracy = 0.932411	<br>
    Kappa = 0.864827</p>
<p>As mentioned above: I tried to not overfit my models. </p>
<p>You can find my other / earlier machine learning attempts on this datasets in the folder <a href = "https://github.com/DJ1070/Hotel_Bookings/tree/main/Machine_Learning">Machine_Learning</a> (but you really don't have to).</p>
