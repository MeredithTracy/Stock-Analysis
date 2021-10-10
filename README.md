# Stock-Analysis
## Overview of Project
The purpose of this project is to help Steve determine the best green energy investments for Steve’s parents. Steve’s parents are wanting to invest all their funds into DAQO New Energy Corp. Our task was to run an analysis using the [Stock Analysis](https://github.com/MeredithTracy/Stock-Analysis/blob/main/VBA_Challenge.xlsm) data on both DAQO (DQ) and other green energy companies to potentially diversify Steve’s parent’s money. 

## Results
![VBA_Challenge_2017_Data](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017_Data.png)

This image shows the total daily volume and return on investment of various companies for the year 2017 


According to the image above, 2017 was a great year for investing in green energy. All but one company finished in the positive. TERP was the only company to finish in the negative. Some stand outs from this analysis were DQ, ENPH, FSLR, and SEDG. All four of these companies had over a 100% return, with DQ coming close to a 200% return. 


![VBA_Challenge_2017_Data](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018_Data.png)

This image shows the total daily volume and return on investment of various companies for the year 2018


According to the image above, this year was a bit tougher overall for green energy companies. All but two companies had an overall negative return. ENPH and RUN continued to finish in the green. DQ specifically had a -62.6% return which in addition to their nearly 200% return from the year prior, still finishes in the green overall over the two years. 

If you were wanting to diversify the funds, investing in ENPH, FSLR, RUN, or SEDG would be good options as they had a very strong year in 2017 and the 2018 performance was either still positive or if it did go negative, the drop would still result in an overall positive investment and you would get a decent return overall. 

## Results from Refactoring Code

![VBA_Challenge_2017_OriginalCode](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017_OriginalCode.png)

This image shows the execution time for the 2017 data from the original code

![VBA_Challenge_2017](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png)

This image shows the execution time for the 2017 data from the refactored code


As you can see from the images above, refactoring code sped up the time needed to execute the same tasks by about .49 of a second for the 2017 data.  


![VBA_Challenge_2018_OriginalCode](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018_OriginalCode.png)

This image shows the execution time for the 2018 data from the original code

![VBA_Challenge_2018](https://github.com/MeredithTracy/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)

This image shows the execution time for the 2018 data from the refactored code


As you can see from the images above, refactoring code sped up the time needed to execute the same tasks by about .53 of a second for the 2018 data. 

These time differences can be fairly significant and would be helpful if we had a larger dataset as well. 

## Summary 

When it comes to refactoring code, there can be advantages and disadvantages. As we can see from above, it can speed up the time needed to run through your code to get your analysis. This can be critical when working in large datasets. It can also simplify the overall code sometimes. You can remove nested loops which can add time to the execution. There can also be some disadvantages as well to refactoring code. When I worked on this analysis in particular, I found while this code is faster, the lines of code became more complex and the potential for errors is higher. It took a couple rounds of debugging to make the updated code work correctly. 

## Limitations

While we have found some answers for Steve, it is important to recognize the limitations to the data. We were only able to look at two years of data. If we wanted to get a clearer answer on if a company continuously does well, we would want to look at more than two years. We are also only looking at twelve green energy companies. We could expand this to look at more options or sort out the data to look at different types of green energy (solar, wind, hydro, etc.) in case Steve’s parents were wanting to invest in a certain area of green energy. 