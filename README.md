BloodBridge: Blood donation and emergency matching platform

CSE327: Software Engineering Project Report

👥 Group Details Group No: 07 Member 1: Anika Bushra — ID: 1811213642 Member 2: Anindho Zaman — ID: 2112423642 Member 3: Mosrur Chowdhury Ornab — ID: 2231868642 Member 4: Labiba Afrida — ID: 2312252042

📝 Project Description Finding a compatible blood donor during emergencies remains a critical challenge, often forcing families to rely on slow, disorganized social media posts or personal networks. Blood Bridge is a centralized, digital solution built to instantly bridge the gap between donors, recipients, hospitals, and blood banks.

The platform allows individuals to register as donors, specify their availability, and track their donation history safely. During an emergency, recipients or hospitals can issue a request specifying blood type and location. The system's matching algorithm immediately notifies nearby eligible, available donors to ensure a swift response.

An administrative panel ensures platform integrity by verifying donor credentials, approving hospital accounts, and filtering out fraudulent requests.

🎯 Target End Users 🩸 Blood Donors 🏥 Hospitals & Blood Banks 👤 Blood Recipients (Patients or Family Members) ⚙️ Administrators

🛠️ System Architecture & Requirements

Key Functional Requirements User Management:** Secure registration, authentication, and role-based profiles. Donor Management:** Live availability toggles, automated eligibility checks, and history tracking. Blood Request Management:** Real-time request creation, geo-location donor search, and automatic matching. Hospital Integration:** Dedicated hospital accounts to request bulk blood or locate specific donors. Admin Controls:** User verification, spam/fake account removal, and automated report generation.

Non-Functional Requirements Security: Encrypted passwords, secure token-based authentication, and role-based access control (RBAC). Usability: Fully responsive mobile and web interfaces. Reliability: High availability (
24
/
7
) with automated database backups. Performance: High-speed donor querying and sub-second push notifications.