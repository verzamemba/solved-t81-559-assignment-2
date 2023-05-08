Download Link: https://assignmentchef.com/product/solved-t81-559-assignment-2
<br>
<h1>Question 1</h1>

Use the dataset found here for this question: <a href="https://github.com/jeffheaton/t81_558_deep_learning/blob/master/datasets_toy1.ipynb">[click for toy dataset].</a>

Encode the <strong>toy1.csv </strong>dataset. Generate dummy variables for the shape and metal. Encode height, width and length as z-scores. Include, but do not encode the weight. If this encoding is performed in a function, named <strong>encode_toy_dataset</strong>, you will have an easier time reusing the code from question 1 in question 2.

Write the output to a CSV file that you will submit with this assignment. The CSV file will look similar to Listing 3.

<h2>Listing 3: Question 2 Output Sample</h2>

<h1>Question 2</h1>

Use the dataset found here for this question: <a href="https://github.com/jeffheaton/t81_558_deep_learning/blob/master/datasets_toy1.ipynb">[click for toy dataset].</a>

Use the encoded dataset from question 1 and train a neural network to predict weight. Use 25% of the data as validation and 75% as training, make sure you shu   e the data. Report the RMSE error for the validation set. No CSV file need be generated for this question.

<h1>Question 3</h1>

Use the dataset found here for this question: <a href="https://github.com/jeffheaton/t81_558_deep_learning/blob/master/datasets_toy1.ipynb">[click for toy dataset].</a>

Using the <strong>toy1.csv </strong>dataset calculate and report the mean and standard deviation for height, width and length. Calculate the z-scores for the dataframe given by Listing 4. Make sure that you use the mean and standard deviations you reported for this question. Write the results to a CSV file.

<h2>Listing 4: Question 3 Input Data</h2>

<ul>

 <li>testDF = pd.DataFrame([</li>

 <li>{’length’:1, ’width’:2, ’height’: 3},</li>

 <li>{’length’:3, ’width’:2, ’height’: 5},</li>

 <li>{’length’:4, ’width’:1, ’height’: 3}</li>

 <li>])</li>

 <li>…</li>

</ul>

Your resulting CSV file should look almost exactly like Listing 5.

<h2>Listing 5: Question 3 Output Sample</h2>

<ul>

 <li>height,length,width</li>

 <li>-0.8822049883269626,-1.5819074849494659,-1.2356589865858818</li>

 <li>-0.18585564084337075,-0.8828608931337095,-1.2356589865858818</li>

 <li>-0.8822049883269626,-0.5333375972258314,-1.5853375067165896</li>

</ul>

<h1>Question 4</h1>

Use the dataset found here for this question: <a href="https://github.com/jeffheaton/t81_558_deep_learning/blob/master/datasets_iris.ipynb">[click for iris dataset].</a>

Usually the <strong>iris.csv </strong>dataset is used to classify the species. Not this time! Use the fields species, sepal-l, sepal-w, and petal-l to predict petal-w. Use a 5-fold cross validation and report ONLY out-of-sample predictions to a CSV file. Make sure to shu e the data. Your generated CSV file should look similar to Listing 6. Encode each of the inputs in a way that makes sense (e.g. dummies, z-scores).

<h2>Listing 6: Question 4 Output Sample</h2>

<ul>

 <li>sepal_l,sepal_w,petal_l,petal_w,species-Iris-setosa,species-Iris- versicolor,species-Iris-virginica,0,0</li>

 <li>30995914214417364, -0.5903951331558184, 0.5336208818725668, 1.2,0.0,1.0,0.0,1.2,1.444551944732666</li>

 <li>-0.1730940663922016, 1.7038864723719687, -1.1658086782311483, <em>–</em></li>

</ul>

0.3,1.0,0.0,0.0,0.3,0.

<ul>

 <li>…</li>

</ul>

<h1>Question 5</h1>

Use the dataset found here for this question: <a href="https://github.com/jeffheaton/t81_558_deep_learning/blob/master/datasets_mpg.ipynb">[click for auto mpg dataset].</a>

Usually the <strong>auto-mpg.csv </strong>dataset is used to regress the mpg. Not this time! Use the fields to predict how many cylinders the car has. Treat this as a classification problem, where there is a class for each number of cylinders. Use a 5-fold cross validation and report ONLY out-ofsample predictions to a CSV file. Make sure to shu e the data. Your generated CSV file should look similar to Listing 7. Encode each of the inputs in a way that makes sense (e.g. dummies, z-scores). Report the final out of sample accuracy score.

<h2>Listing 7: Question 4 Output Sample</h2>

<ul>

 <li>mpg,cylinders,displacement,horsepower,weight,acceleration,year,origin,name ,ideal,predict</li>

 <li>-0.7055506566787514, 8, 1.0892327311042995, 0.6722714619460141, 6300768256149949, -1.2938698102195594, 70, -0.7142457922976494, chevrolet chevelle malibu,8,8</li>

 <li>-1.0893794720944747, 8, 1.5016242793620063, 1.5879594901955474, <em>–</em></li>

</ul>

0.8532590135498572, -1.4751810504376373, 70, -0.7142457922976494,buick skylark 320,8,8

<ul>

 <li>-0.7055506566787514, 8, 1.1947282434492943, 1.19552176380289, <em>–</em></li>

</ul>

0.5497784722839334, -1.6564922906557151, 70, -0.7142457922976494, plymouth satellite,8,8

<ul>

 <li>…</li>

</ul>