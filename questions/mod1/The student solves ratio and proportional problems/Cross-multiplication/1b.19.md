## Slot 19: quiz
### Score

1

### Task: wgu_a1bs19_Server Capacity Scaling_m7R4p

#### Task Description

**Given:** A statistical computing cluster uses 4 servers to process 1,200 data queries per minute. A research team needs to determine capacity requirements for increased workload.

How many servers are needed to process 4,500 data queries per minute?

#### Quiz Options

###### Option 1 Incorrect
3.75


###### Option 2 Incorrect
8


###### Option 3 Correct
15


###### Option 4 Incorrect
16


#### Quiz Settings

```json
{
  "shuffleOptions": false,
  "multipleChoice": false,
  "hasNoneOfTheAbove": false
}
```


#### Internal Notes

##### Competency
The student applies quantitative operations to solve real-world problems.

##### Evidence Statement
The student solves ratio and proportional problems.

##### Aligned Content
Cross-multiplication

##### Explanation
Set up a proportion: $\frac{4}{1,200} = \frac{x}{4,500}$. Cross-multiply: $1,200x = 4 \times 4,500 = 18,000$. Solve for $x$: $x = \frac{18,000}{1,200} = 15$ servers.

##### Distractors
###### Option 1
Identifies the scale factor but fails to complete the operation. The student correctly calculates that the workload has increased by a factor of 3.75 ($4,500 \div 1,200 = 3.75$) but provides the multiplier itself as the answer rather than multiplying it by the original server count.

###### Option 2
Doubles the servers instead of applying the correct scale factor. Students may recognize that 4,500 is larger than 1,200 and incorrectly apply a standard "doubling" heuristic ($4 \times 2 = 8$) without calculating the exact ratio.

###### Option 4
Overestimates the scaling requirement. The student may miscalculate the scale factor as 4 instead of 3.75, or mistakenly use the initial number of servers as the multiplier ($4 \times 4 = 16$) because the target workload is significantly higher.


