# School_District_Analysis
School District Analysis - Module 4

## Overview
Review of school and student data/analysis initially prepared for stakeholders has resulted in concerns regarding altered grades for ninth grade students at Thomas High School.  As a result, potentially
altered grades have been replaced and analysis reperformed in order to show how results have been impacted.  

## Results
1.  Replacement of potentially invalid math and reading grades for Thomas High School ninth grade students, removing them from calculations
2.  Repeat of original school district analysis
	1) District Summary - because the number of Thomas High School ninth grade students is small in relation to the total number of students in the district, impact to the 	District Summary by removal of potentially impacted grades is minimal.

		Original District Summary:
		![District Summary w/ Thomas High 9th Grade](/Resources/Image_Orig_District_Summary.png)

		Adjusted District Summary:
		![District Summary w/out Thomas High 9th Grade](/Resources/Image_Adj_District_Summary.png)
  
	2) School Summary - because potentially invalid grades are all from Thomas High School, impact to their calculations is apparent. Other schools are unaffected.

		Original School Summary:
		![School Summary w/out Thomas High 9th Grade](/Resources/Image_Orig_School_Summary.png)
	
		Adjusted School Summary:
		![School Summary w/out Thomas High 9th Grade](/Resources/Image_Adj_School_Summary.png)
	
	3) Top five/bottom five schools based on student overall passing rate - removing grades for ninth graders at Thomas High School has moved the school into the Top 5 based 	  on Overall Passing %.  Bottom Five schools are unaffected.

		Top Five Schools:
		![Top 5 Schools based on Overall Passing %](/Resources/Image_Adj_Top_Five.png)
	
		Bottom Five Schools:
		![Bottom 5 Schools based on Overall Passing %](/Resources/Image_Orig_Bottom_Five.png)
	
	4) Average math score, by school, by grade level - removing grades for ninth graders at Thomas High School results in the "nan" value seen in the table
		
		![Average math score, by school, by grade level](/Resources/Image_Math_by_gradelevel.png)
	
	5) Average reading score, per school, by grade level - removing grades for ninth graders at Thomas High School results in the "nan" value seen in the table

		![Average reading score, by school, by grade level](/Resources/Image_Reading_by_gradelevel.png)
		
	6) Scores, by school spending per student - impact of removing grades of ninth graders at Thomas High School is minimal

		![Scores by School Spending Per Student](/Resources/Image_Spending.png)

	7) Scores, by school size - impact of removing grades of ninth graders at Thomas High School is minimal
	![Scores by School Size](/Resources/Image_Size.png)
	8) Scores, by school type - impact of removing grades of ninth graders at Thomas High School is minimal
	![Scores by School Type](/Resources/Image_Type.png)
	

## Summary
The impact of removing scores for ninth graders at Thomas High School varies across metrics.  In metrics where schools are evaluated and compared based on all student scores, such as the School Summary and Top 5 Schools, the impact is significant, particularly for Thomas High School.  This is shown by the noticeable increase in percentage scores for Thomas High School and it being included as a Top 5 school after these grades were removed.  Impact to metrics based on grade level is also signficant, as analysis and comparisons for ninth grade students are not possible without the Thomas High School ninth grade data.  Conversely, there is no impact to metrics based on grade level for students in tenth, eleventh, and twelfth grades.  Finally, there are metrics where impact is minimal due to the relatively small number of grades being removed to total grades available for analysis, with the most obvious of these being the District Summary.
