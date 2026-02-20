Problem 1 – Monthly Budget Analyzer

Maine kya kiya:

Monthly expenses ko alag variables me store kiya: Rent, Food, Transport, Utilities

Total monthly expense calculate kiya sab ko add karke

Total expense ko budget limit (60,000 PKR) se compare kiya

Print kiya ke student Within Budget hai ya Over Budget

Logic:

Arithmetic operations total nikalne ke liye

if-else use karke budget check kiya

Challenges:

Simple problem thi, koi major challenge nahi

Problem 2 – Electricity Bill Estimator

Maine kya kiya:

User se electricity units ka input liya

Conditions apply ki:

≤100 → Basic Rate

101–300 → Standard Rate

300 → High Usage Rate

Billing category print ki

Logic:

if-elif-else multiple conditions ke liye

input() se data lena

Challenges:

Condition ranges sahi tarah set karna, overlap avoid karna

Problem 3 – Class Attendance Analysis

Maine kya kiya:

Attendance percentages list me store ki

Loop ke zariye count kiya: students meeting attendance (≥75%) aur jo nahi meet karte

Dono counts print kiye

Logic:

List ke upar loop

Counters use kiye eligible aur non-eligible students count karne ke liye

Loop ke andar conditional check

Challenges:

Dono counters ko correct update karna

Problem 4 – Scholarship Eligibility System

Maine kya kiya:

CGPAs aur family incomes parallel lists me store kiye

Index ke zariye iterate kiya

Compound condition check ki: CGPA ≥3.5 aur income ≤80,000 PKR

Total eligible students count kiye

Logic:

Loop + compound condition (and)

Index-based access to parallel lists

Challenges:

CGPA aur correct income match karna

Index off-by-one errors avoid karna

Problem 5 – Sensor Alert System (Bonus)
Maine kya kiya:

Sensor readings list me store kiye

Count kiya readings jo safe range (20–80) se bahar hain

Percentage calculate ki alert readings ka

Total alerts aur percentage print ki

Logic:

Loop + accumulator

or condition for readings <20 ya >80

Percentage calculation using arithmetic

Challenges:

Correctly identify readings outside range

Percentage calculate karna total readings ke base par