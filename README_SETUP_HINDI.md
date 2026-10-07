# JeevanSetu College Live Demo

1. Firebase Authentication → Email/Password ON.
2. Firestore Database → create database.
3. Firestore Rules में इस ZIP की `firestore.rules` publish करें.
4. GitHub Pages में ZIP के root files upload करें.
5. दोनों phones पर same live URL खोलें.
6. Phone 1 receiver account, Phone 2 donor account बनाएं. Same blood group + same State + same District रखकर request भेजें.
7. Donor ACCEPT करेगा; receiver के Requests में live Accepted + Call/WhatsApp दिखेगा.
8. Profile → Switch Role और My Connections भी demo करें.

Demo के लिए केवल अपने test accounts इस्तेमाल करें; bundled dummy donor data नहीं है. Real patient/medical data नहीं डालें.


## Permission Gate
For the college demo, Location, Notifications and Camera permissions are mandatory. If the user presses Deny on any permission, JeevanSetu stays on the permission screen and does not open the main app. The user must change the browser/site permission to Allow and then press Check & Continue.
