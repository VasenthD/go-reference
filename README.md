# Time in go

currentTime := time.Now()

-> this is how you can get the current time in go
-> we can get the year by 

currentTime := time.Now()
year := currentTime.Year()

// the current year will be stored in the year variable
but it will not be in the string formate it will be INT formate so 

currentTime := time.Now()
	year := currentTime.Year()
	year1 := strconv.Itoa(year)
	if x == year1 {
		fmt.Printf("Current year: %d\n", year)
	}else{
		fmt.Println("wrong year ")
	}
