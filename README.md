CatchUp 🚀 (Catchup-with-AI)

Missed class? Catch up in minutes.

CatchUp is a single-file web app that helps a student who was absent from class find out what happened. Classmates, teachers, peer mentors and class representatives post recaps, deadlines and reminders in a separate chat for each class, so the absent student has everything in one place.

Everything lives in one self-contained file: catchup.html. There is nothing to install and no server to run.

✨ Features
👋 Login and greeting
Enter your name and choose your role: Classmate, Teacher, Peer Mentor or Class Rep.
A time-of-day greeting ("Good morning, Sam 👋") opens the app.
A "What's new" popup appears at login and when you return. It lists the latest updates from each class with a "new" badge. Tap a class to jump straight in, or choose Mark all read.
📚 Multiple classes
＋ New class creates a separate chat for each class. You choose a name, an icon and a color, and you can add people right away.
The 🗑 button deletes a class chat (with a confirmation), which is handy when a new semester starts.
Class cards show how many people and updates each class has, plus unread badges. The 🔔 button shows your total unread count.
📝 Updates by type

Each post is tagged so important things stand out:

Tag	Use it for
📝 Recap	A summary of what happened in class
🎯 Exam	Exam dates and details
⚡ Quiz	Upcoming quizzes
🏅 Mastery Check	Mastery checks
📚 Homework	Assignments and due dates
🎒 Bring	Things to bring to the next class (with tick-off checkboxes)

Filter chips at the top of each chat show only one type. Each post shows who wrote it, their role and when. New updates from others are outlined until you leave the chat.

📎 Uploading information
Attach a photo (for example a picture of the board) or a file (PDF, Word, PowerPoint or text) with the 📎 button.
Paste a screenshot straight into the message box.
Photos are resized automatically. Other files can be up to 400 KB.
Images display in the chat and files get a download link. You can send an attachment without any text.
👥 Adding members
Open 👥 inside a class to see who is in it.
Add one person, or several at once separated by commas (Jordan, Mia, Mr. Lee). Duplicate names are skipped.
You can also add people when creating a class.
Remove anyone with the ✕ button. When you post an update, you choose who it is posted as.
🎨 Design
Modern gradient look with rounded cards.
Automatic dark mode, plus a 🌓 toggle.
Works on phones and desktops.
🚀 How to use
Download catchup.html.
Open it in any modern browser (Chrome, Edge, Safari, Firefox).
Enter your name, pick your role, and tap Let's go.
Tap ＋ New class, open it, and start posting updates.
🛠 Built with
Plain HTML, CSS and JavaScript, with no frameworks and no build step.
Data is saved in the browser's localStorage.
The Outfit font loads from Google Fonts, with system fonts as a fallback.
⚠️ Known limitations
No shared backend. Data is saved only in the browser on the device you use, so other people on their own devices won't see your updates. Today the app is best used as a personal tracker, or by one person entering updates on behalf of the group.
Browser storage is limited (roughly 5 MB), so many attachments can fill it up. The app warns you if that happens.
Clearing your browser data removes your classes and updates.
The demo class "Biology 101" is created at first login so you can see how things look.
🔮 Ideas for the future
Real-time shared chats with a backend (accounts, invite links)
Real push notifications
Calendar view of exams, quizzes and homework deadlines
AI-generated recap from pasted class notes
Export a class's updates as a PDF
🤖 How it was made

This project was built with AI assistance using Claude (Anthropic).

Prompt 1 – Initial build

Act as an experienced app builder, goal build a easy to use app, requirements: easy to use, Creative modern design for the app, working buttons, Give it a creative name, Idea for the, it has to be a one self contained HTML FILE, App: this app is for a student who was absent for the class, in this app it can be a class mate, teacher, peer mentor or a class representative, give a summary of what happened in the class, any important information regarding the subject like exam, quiz, mastery check or homework. Anything that we need to bring for the next class. it can have multiple class, like has a button that allows you to create a individual chat for each class with multiple people in it and delete button for those chats as students add new class every semester, also when you login it can open up with a small greeting.

Prompt 2 – Enhancement

Enhance the app by ensuring all users can seamlessly upload information and add new members, and implement instant login notifications that immediately display the latest updates from class groups.

Follow-up fixes: Between the two prompts, some popup buttons and the add-member button did not respond, which was fixed. After prompt 2, a typo broke the whole app, which was also fixed.

AI tool: Claude

👤 Author
Mokshita varma Varada raju.
