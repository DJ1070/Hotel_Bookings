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
<p>The dataset stems from 2 Portugese hotels, a city and a resort hotel. It contains overnighters from the years 2015, 2016, and 2017 as well as cancelled bookings.</p>


<h2>My Approach</h2>
<p>Ich bin mit Fragen aus dem Marketing an den Datensatz herangegangen. Ich selbst komme aus dem Marketing und habe mich in den letzten 20+ Jahren mit der Erforschung von User- und Käuferverhalten befasst. Somit habe ich zwar auch, aber eben nicht nur typische KPIs formuliert. Die Daten enthalten zahllose Hinweise auf menschliche Bedürfnisse und Verhaltensweisen. Daten können vieles nicht beantworten, aber sie werfen sehr oft Fragen auf, die es sich im Anschluss an die Datenanalyse zu beantworten lohnt, denn daraus ergeben sich die wichtigsten Hinweise für das strategische Marketing.</p>


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


<h2>Machine Learning</h2>
