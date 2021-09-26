# School_District_Analysis

## Overview

The purpose of the original analysis was to determine the performance of schools within the district based on multiple factors. The performance of the school is determined by reading and math scores which were further broken down into average scores per grade. The factors are budget per student, school size, and type of school. Unfortunately, the ninth-grade students within Thomas High School have been suspected of academic dishonesty concerning their math and reading scores. Due to the academic dishonesty, the school board would like to run the original analysis but to remove the ninth-grade class.

## Results

The district summary wasn't affected at all, the district summary with the ninth-grade class is identical to the summary without the class. As seen below, nothing has changed between the two analyses.

![district_summary_with9th](https://user-images.githubusercontent.com/87910875/134793583-c35d7fe6-1c61-48a0-aaea-31773496d89e.png)

![district_summary_without9th](https://user-images.githubusercontent.com/87910875/134793584-8ca28168-2fbe-418a-95bf-d61cf1f54772.png)


The school summary drastically decreased due to removing the ninth-grade class. As seen in the image, Thomas High School was one of the top-performing schools. They had a high percentage of students passing math and reading.
![thom_hs_school_summary_with9th](https://user-images.githubusercontent.com/87910875/134793183-ce285b2e-4788-4eeb-b664-48d3c7fe2359.png)

This is compared to after removing the ninth-grade class where the overall passing percentage decreased significantly. As seen in the image below, Thomas High School has lost its previously inflated overall passing percentage.

![thom_hs_school_summary](https://user-images.githubusercontent.com/87910875/134793231-9a6bc834-195f-4411-ae4e-6c71999ed154.png)

Math scores by grade were not affected other than replacing the ninth-grade scores with "nan".

![math_scores_by_grade](https://user-images.githubusercontent.com/87910875/134794244-83f34ce9-b808-4e26-86ac-45ec2711d35a.png)

Reading scores by grade were not affected other than replacing the ninth-grade scores with "nan".

![reading_scores_by_grade](https://user-images.githubusercontent.com/87910875/134794253-3182d1f6-4699-47a1-a781-33f961e903d6.png)

Scores by school spending were also not affected by removing the ninth-grade class. As seen below, Thomas High School stayed within the $630-644 budget per student range.

![scores_by_spending_new](https://user-images.githubusercontent.com/87910875/134794265-0b8dd4be-e388-4658-bb99-34e96a6f6827.png)


Scores by school size also remained unchanged as seen in the image below.

![school_size_new](https://user-images.githubusercontent.com/87910875/134794270-d7da6e6c-d6f8-4022-a859-e99581fef113.png)

Scores by school type are also unchanged from the original analysis.

![scores_by_type_new](https://user-images.githubusercontent.com/87910875/134794278-fb253e1f-126e-4d2e-b462-fa370bf01b19.png)

## Summary

Only the school summary was affected between the two analyses whereas the district analysis was overall unaffected. The first change was the different in overall passing percentage when initially dropping the ninth-grade class. Another change was made when I replaced the average scores with just students between 10th grade and 11th grade. The replacement of scores caused Thomas High School to return to their previous standing due to the result scores being close to the original scores.


