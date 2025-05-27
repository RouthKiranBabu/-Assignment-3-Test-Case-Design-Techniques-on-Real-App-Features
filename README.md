- Given Task
    - [Task](https://github.com/RouthKiranBabu/-Assignment-3-Test-Case-Design-Techniques-on-Real-App-Features/blob/main/Assignment.png)
 - Completed Work
    - [PDF](https://github.com/RouthKiranBabu/-Assignment-3-Test-Case-Design-Techniques-on-Real-App-Features/blob/main/%E2%9C%85%20Assignment%203_%20Test%20Case%20Design%20Techniques%20on%20Real%20App%20Features.pdf)
    - [Document](https://github.com/RouthKiranBabu/-Assignment-3-Test-Case-Design-Techniques-on-Real-App-Features/blob/main/%E2%9C%85%20Assignment%203_%20Test%20Case%20Design%20Techniques%20on%20Real%20App%20Features.docx)

# 🧭 Setup
 - Install Flipkart app.
 - Do the Pre-requisite shown in pdf/word.
# 🛠️ Build Commands
 - Since this is manual testing theres is no need of tools.
# 🗒️ Description of Functionalities
## 🟰 Equivalence Partitioning
In this method, we try to reduce human effort by taking all possible inputs seperating into groups, where each group shows the same behavior of element/system, so that we may/can remove samples in the group, which improves speed of project completion. Ensuring analysing all the behavior is not hidden.
<div align="center">
  
|Test Case ID |Phone Number Length| Continue button(Is Active)|
|:--|:--:|--:|
|TC_0001| 1 to 9| Inactive|
|TC_0002| 10 to 15| Active|
|TC_0003| 16 to -| Inactive|
</div>

## 🧱 Boundary Value Analysis
- In this approach, we need to find the edge/boundary where the system/element/behavior changes, then checking its incremental and decremental behavior in opposite direction irrespected of magnitude incremented/decremented, which finally reduces number of test cases to be tested.

<div align="center">
  
|Test Case ID |Phone Number| Length Continue button(IsActive)|
|--:|:--:|:--:|
|TC_0007| 9| Inactive |
|TC_0008 |10| Active|
|TC_0009| 11| Active|
|TC_0010| 14| Active |
|TC_0011| 15| Active |
|TC_0012 |16 |Inactive|
</div>

## 💭 Decision Table
 - In this approach
