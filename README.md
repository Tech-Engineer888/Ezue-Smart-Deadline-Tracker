
# 📅 Ezue Smart Deadline Tracker

**AI-powered legal deadline tracker** for monitoring statutory, procedural, and contractual timelines across litigation, transactions, and compliance matters.

Built by a lawyer for lawyers, this Streamlit-powered assistant helps you stay ahead of deadlines that matter — from pre-action notices and appeals to contract milestones and regulatory filings.

---

## 🚀 Features

- 📋 Input case/matter-specific deadlines (court filings, contracts, compliance dates)
- ⏰ Auto-calculate deadlines from trigger/start dates
- ⚠️ Automatically flags overdue items
- 📊 Displays all entries in a structured table
- 📤 Export tracker data as CSV
- 🔒 Runs fully client-side (no database required)

---

## 💼 Use Cases

| Area | Example Deadlines |
|------|-------------------|
| Litigation | Pre-action notice, defence, reply, notice of appeal |
| Transactional | Contract renewal, lease expiration, deal closing |
| Compliance | CAC filings, regulatory submissions, license renewals |

---

## 🛠 Built With

- Python  
- Streamlit  
- Pandas  
- Deployed on [Streamlit Cloud](https://streamlit.io)

---

## 🔧 Run Locally

```bash
git clone https://github.com/Tech-Engineer888/ezue-smart-deadline-tracker.git
cd ezue-smart-deadline-tracker
pip install streamlit pandas
streamlit run app.py
