#Hypothyroidism Clinic Camp Analysis at Nairobi Hospital

Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroidism.

##Part 1
- Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid. Make use of at least 2 out of 3 advanced models : Random forests, Ada boosted trees, and gradient boosted trees.

- Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.

- Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction.

##Part 2
- Document what transformation you've done on the data.

- Apply Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best. Remember to tune your parameters to improve the performance of your model. To make your life easier, make sure to visualize the models you've created. Use any two features to build the models for this step.

Hint: You may want to use decision trees to give you the most preferable features you can use. but also keep in mind that those features might not be suitable for SVM. It might be a good idea to graph them first.

- After getting your best performing kernel, use this kernel together with your tuned parameters and repeat the prediction but this time using additional features. Compare the model you've just created with the 2-features version.
