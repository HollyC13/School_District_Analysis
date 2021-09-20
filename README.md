# School_District_Analysis
School District Analysis - Module 4

# School District Analysis
Module 4 - PyCitySchools with Pandas

## Overview
Review of school and student data/analysis initially prepared for stakeholders has resulted in concerns regarding altered grades for ninth grade students at Thomas High School.  As a result, potentially
altered grades have been replaced and analysis reperformed in order to show how results have been impacted.  

## Results
1.  Replacement of potentially invalid math and reading grades for Thomas High School ninth grade students, removing them from calculations
2.  Repeat of original school district analysis
    a)  District Summary - because the number of Thomas High School ninth grade students is small in relation to the total number of students in the district, impact to
        the District Summary by removal of potentially impacted grades is minimal.

	Original District Summary:
	![District Summary w/ Thomas High 9th Grade](/Resources/Image_Orig_School_Summary.png)

	Adjusted District Summary:
	![District Summary w/out Thomas High 9th Grade](/Resources/Image_Adj_School_Summary.png)
  
    b)	School Summary - because potentially invalid grades are all from Thomas High School, impact to their calculations is apparent.  Other schools are unaffected.
    c)  Top five/bottom five schools based on student overall passing rate - removing grades for ninth graders at Thomas High School has moved the school into the Top 5 based on Overall Passing %
    d)  Average math score, per school, by grade level
    e)  Average reading score, per school, by grade level
    f)  Scores, by school pending per student
    g)  Scores, by school size
    h)  Scores, by school type
