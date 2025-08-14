🛒 Kroger Members Dataset

📄 Overview

The Kroger Members Dataset contains information on customer membership status within the Kroger loyalty program.
It can be used for:

Membership penetration analysis

Customer segmentation

Marketing campaign targeting

📂 File Details

Filename: kroger_members.csv

Total Records: 100

Total Columns: 2

📊 Data Dictionary
Column Name	Data Type	Description
kroger_id	Integer	Unique identifier for each Kroger customer. Acts as the primary key.
has_member_card	String (Y or blank)	Indicates membership status:
• Y → Customer has a membership card
• (blank) → No membership card


📝 Sample Data
kroger_id	  has_member_card
1	          Y
2	          Y
3	          (blank)
4	          Y
5	          (blank)


📈 Potential Analyses

Membership Penetration Rate → Percentage of customers with has_member_card = 'Y'

Targeted Outreach → Identify and target customers without a membership

Behavior Analysis → Combine with transaction data to study spending patterns of members vs non-members

pie chart for membershi and non-membership:
<img width="850" height="856" alt="kroger_membership_pie (1)" src="https://github.com/user-attachments/assets/97d9d0f1-de1e-4fc3-8ae0-fc8a6f4b094d" />


