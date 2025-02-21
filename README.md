In this repository you can find the code we used to run the montecarlo simulation for the Ocean Carriers case.
All the values assumed and assigned to the variables are explicitly written (i.e. number of iterations, standard deviations assumed etc.).
Any number hard-coded comes from calculations performed in excel, which we did not perform again to save computational power and make the code run faster.
Assumptions are the followhing: inflation and hire rates growth are normally distributed; past inflation and growth rates affect future values, thus normal distributions are centered around a rolling average; standard deviations of the normal distributions increase logarithmically over time to capture the uncertainty of estimated values in further years.
