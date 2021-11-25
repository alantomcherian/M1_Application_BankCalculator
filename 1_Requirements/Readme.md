# Requirements

---

## Features

---

- Generates Total Amount by inserting amount , rate , duration .
- No need of manual calculation as it is capable of compounding interest quarterly to initial amount .
- Saves time, as it can do calculations which otherwise had to be done manually .

## Research

---

Some 20 years ago banks officers used notebook and pen to do calculate compound interest. All calculations were manual which is time consuming process with higher chances of error .

Some 10 years ago banks officers used calculators to do compute the compound interest. Calculations were still a time consuming process with moderate chances of error .

Bank officers will compute compound interest in the bank calculator app as it is less erroneous and and a time-saving process.

## 4W and 1H

---

### What

Application is designed to be implemented in bank computers and kiosks . It will help the user to generate total amount after quaterly compounding.

### Why

In banks total amount calculation is done using calculators which is an erroneous and a time-consuming process. This app overcomes all that.

### Where

Application is designed to be implemented in bank computers and kiosks .

### How

Bank application will take input from user such as initial amount, rate and duration which then proceeds to compute the final amount after calculating quaterly compound interest .

## SWOT Analysis

---

#### Strengths

- Time saving process
- No chance of errors in calculation if the inputs are right

#### Weaknesses

- Cannot calculate for premature withdrawal.

#### Opportunities

- Can be implemented in any type of bank

#### Threats

- Other Similar Applications

## High Level Requirements

---

| HLR   | Description                                                                                | Status      |
| ----- | ------------------------------------------------------------------------------------------ | ----------- |
| HLR_1 | App will able to do the calculations required to generate total amount                     | Implemented |
| HLR_2 | App will able to do the calculations required to generate quarerly compounded interest     | Implemented |

## Low Level Requirements

---

| LLR HLR_1   | Description                                                     | Status      |
| ----------- | --------------------------------------------------------------- | ----------- |
| LLR_1 HLR_1 | Get data from standard input                                    | Implemented |
| LLR_2 HLR_1 | Compute the compounded interest by doing appropriate operations | Implemented |
| LLR_3 HLR_1 | Pass the compounded interest to final amount calcuation         | Implemented |

| LLR HLR_2   | Description                                                        | Status      |
| ----------- | ------------------------------------------------------------------ | ----------- |
| LLR_1 HLR_2 | Add the quarterly compounded interest to the initial amount        | Implemented |
| LLR_2 HLR_2 | Return the final amount                                            | Implemented |
