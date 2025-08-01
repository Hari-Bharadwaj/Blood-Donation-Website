# Create the README.md content based on the previous assistant message

readme_content = """
# Blood Donation Registration & Awareness Website

This is a basic web application built in ~30 minutes during a **KL University Hackathon**.  
The goal of the project is to provide a platform for users to **register as blood donors**, **learn about donation**, and **connect with recipients or organizers**.

It uses **JSP**, **HTML**, **CSS**, and simple static assets — ideal for a demo or prototype of a blood donation awareness initiative.

---

## 🩸 Features

- 🧾 **Donor Registration** via `Apply.jsp`
- 🔍 **Donor Information Lookup / Validation** via `Check.jsp`
- 🙋‍♂️ **User Login and Sign-up** (`Login.jsp`, `Register`)
- 📬 **Contact Page** for queries or support
- 💝 **Donation Page** to promote involvement
- 📄 **Minimal DAO Logic** simulated in `DAO.jsp`
- 🌐 **Awareness Content** and Static Pages
- 📦 Basic file-based structure — no database integration (for simplicity)

---

## 📁 Folder Structure

.
├── css/ # Stylesheets
├── images/ # Images (e.g. blood.png, hand.png, think.png)
├── WEB-INF/ # Configuration directory (JSP/WebApp structure)
├── Apply.jsp # Blood donor registration form
├── Check.jsp # Record validation or listing
├── ContactMe # Contact page (static or JSP)
├── DAO.jsp # Simulated backend logic
├── Donate.jsp # Donation page content
├── HOME.jsp # Homepage layout
├── Login.jsp # Login form
├── Register # Registration page
├── index # Main landing page (alias/home)
├── Other assets # PNGs: hand, blood, donate, think

yaml
Always show details

Copy code

---

## 🚀 How to Run

> This is a JSP-based app. To run it locally:

1. Download and install [Apache Tomcat](https://tomcat.apache.org/).
2. Place the project folder inside `webapps/`.
3. Start the Tomcat server.
4. Visit: `http://localhost:8080/your-folder-name`

---

## 📌 Hackathon Notes

- ⏱ Built in **under 30 minutes** during a rapid-prototype session.
- 🧑‍🤝‍🧑 Focused on usability and awareness, not backend persistence.
- 🔧 Could be extended with database (e.g., MySQL) or real-time matching features.

---

## 📄 License

This project is open for use and adaptation.  
Feel free to fork or extend it. If you use this in a project or presentation, a mention would be appreciated!

---

## 🙋‍♀️ Team & Acknowledgements

Developed by a student team at **KL University** during a campus hackathon.  
Thanks to the organizers and mentors who supported the event.
"""

# Save it as a file
readme_path = "/mnt/data/README_BloodDonationWebsite.md"
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path
