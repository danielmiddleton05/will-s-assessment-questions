## Slot 9: quiz
### Score

1

### Task: wgu_a1as9_Equal Team Distribution_7mK9p

#### Task Description

**Given:** A data analyst needs to divide 168 survey responses equally among review teams with no responses left unassigned. Each team will split their assigned responses into 3 equal groups for a staged review process.

Which number of teams satisfies both requirements?

#### Quiz Options

###### Option 1 Incorrect
11


###### Option 2 Correct
14


###### Option 3 Incorrect
21


###### Option 4 Incorrect
24


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
The student determines factors, multiples, and factorizations.

##### Aligned Content
Factors & divisibility

##### Domain
Business

##### Explanation
Prime factorize the total responses:
$$
168 = 2^3 \times 3 \times 7
$$

To distribute with no remainder, the number of teams must be a factor of 168.

To ensure the responses per team are divisible by 3, the quotient $\frac{168}{\text{teams}}$ must still include a factor of 3. Since 168 has only one factor of 3, the number of teams cannot include a factor of 3.

- $14 = 2 \times 7$ is a factor of 168 and does not include 3, so the quotient keeps the factor of 3:
$$
168 \div 14 = 12
$$
And $12$ is divisible by $3$. Therefore, 14 teams satisfies both conditions.

##### Distractors

###### Option 1
Students may confuse "prime number" with "factor" or assume a nearby number divides evenly without checking factor structure.  
Because $11$ is not part of $168=2^3\cdot3\cdot7$, it is not a factor of 168.

###### Option 3
While $21$ is a factor ($21 = 3 \times 7$), it uses the only factor of 3 in 168:
$$
168 \div 21 = 8
$$
and $8$ is not divisible by 3.

###### Option 4
Although $24$ is a factor ($24=2^3\times3$):
$$
168 \div 24 = 7
$$
and $7$ is not divisible by 3.


