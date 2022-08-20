# Credit-Risk
1) Load the data
2) check the data frame shape to know the number of rows and columns
3) name 2 loaded files as:
		app_rec (application record)
		cre_rec (credit record)
4) Start with app_rec:
	check the columns' name
	check the datatype of each column and the number of values\missing values in each column (.info())
	create one-hot encoding for 'NAME_INCOME_TYPE','NAME_EDUCATION_TYPE','NAME_FAMILY_STATUS','NAME_HOUSING_TYPE'
	Replace the missing values for 'OCCUPATION_TYPE' with "Other"
	change the data type of 'ID','FLAG_MOBIL', 'FLAG_WORK_PHONE', 'FLAG_PHONE', 'FLAG_EMAIL'
	check the min, max, mean, count, std for the numeric fields

	