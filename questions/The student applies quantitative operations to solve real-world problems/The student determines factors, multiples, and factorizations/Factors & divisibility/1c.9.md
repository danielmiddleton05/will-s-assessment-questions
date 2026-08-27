## Slot 9: quiz
### Score

1

### Task: wgu_a1cs9_Hospital Supply Order Divisibility_r3Kn7

#### Task Description

A hospital supply manager orders bandage rolls. The order will be divided equally among 9 storage rooms. Each room's rolls will then be split equally into 7 daily-use bins, and each bin must contain an even number of rolls.

Which order quantity satisfies all three conditions?

#### Quiz Options

###### Option 1 Incorrect
189


###### Option 2 Incorrect
196


###### Option 3 Incorrect
210


###### Option 4 Correct
252


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
Healthcare

##### Explanation
Each order quantity must satisfy three divisibility conditions:

1. The total must be divisible by 9 (equal split among storage rooms).
2. Each room's share must be divisible by 7 (equal split into daily bins).
3. Each bin's share must be even (even number of rolls per bin).

Check 252:
$$252 = 2^2 \times 3^2 \times 7$$

- $252 \div 9 = 28$ → divides evenly ✓
- $28 \div 7 = 4$ → divides evenly ✓
- $4$ is even ✓

Therefore, an order of 252 bandage rolls satisfies all three conditions.

##### Distractors

###### Option 1
Students may check only the first two conditions and stop. $189 = 3^3 \times 7$, so it is divisible by 9:
$$189 \div 9 = 21$$
and $21$ is divisible by $7$:
$$21 \div 7 = 3$$
However, $3$ is odd, so the third condition (even number per bin) is not met.

###### Option 2
Students may focus on the factor of 7 and overlook the first condition. $196 = 2^2 \times 7^2$, which contains factors of 7, but:
$$196 \div 9 \approx 21.78$$
This is not a whole number, so the total cannot be divided equally among 9 rooms.

###### Option 3
Students may recognize that $210 = 2 \times 3 \times 5 \times 7$ contains factors of 7 and assume it also works for 9. However:
$$210 \div 9 \approx 23.33$$
This is not a whole number, so the total cannot be divided equally among 9 rooms. While $210$ is divisible by $7$, that alone is not sufficient.


