# P&P Serverless Matrix Link

A decentralized hub for sharing .sav cartridge files. No servers, no registration—just the clipboard and files.
<img width="1853" height="903" alt="P and p serverless matrix link" src="https://github.com/user-attachments/assets/283f57fa-5333-4b77-8286-ec9aab8b7a9f" />

🛠️ How does this pipeline work?

I don’t have the money for a backend or a database to host your games. So, I’ve shifted the workload onto you and the file system.
Serverless Matrix Link is a simple website. It takes the metadata you enter (nickname, title) and the attached .sav file, packages them into a text-based Matrix link, and allows others to download the file.

⚠️ Limitations of this site

• Yes, there is no automatic over-the-air installation. You have to download the file and manually move it to the folder.

• Fully open-source by default: You can’t encrypt or hide your code inside the `.sav` file. Anyone you share the cartridge with can dig into your scripts you used.
