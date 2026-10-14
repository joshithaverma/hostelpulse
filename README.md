[README.md](https://github.com/user-attachments/files/33440500/README.md)
# hostelpulse# HostelPulse

A light-mode hostel management demo built with HTML, CSS, and vanilla JavaScript, themed for CVR College of Engineering hostels.

This is a student project prototype, not an official college service.

## Features

- Separate student and warden demo sign-in screens and logout
- Attendance tracking and report exports
- Outing requests and outpasses
- Mess menus, polls, and feedback
- Maintenance requests and laundry tracking
- Lost & Found posts with optional image uploads and previews
- Hostel announcements and medical-alert demonstration
- Light-only interface with responsive layouts

## Run locally

Download this repository and open `index.html` in Chrome or Edge. No installation or build step is required. An internet connection is needed for the optional Google Fonts stylesheet; system fonts are used otherwise.

## Demo accounts

| Portal | Username | Password |
| --- | --- | --- |
| Student | `student` | `Student@123` |
| Warden | `warden` | `Warden@123` |

Select the matching portal on the sign-in screen. Log out before signing into the other role.

## Photo uploads

In Lost & Found, choose an optional JPG, PNG, or WebP image up to 8 MB. Preview or remove it before posting. Images are resized and stored with the post in browser storage.

## Publish with GitHub Pages

1. Create a repository named `hostelpulse` on GitHub.
2. Upload the files inside this folder to the repository root, including `index.html` and this README. Do not upload the ZIP as your website.
3. Open repository **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. When deployment completes, use the website URL shown in Pages settings.

## Project files

```text
index.html   Complete application, including styles and scripts
README.md    Project overview and setup instructions
.gitignore   Common local-file exclusions
.nojekyll    Serve the application as plain static files
```

## Demo limitations

- Login is a client-side demonstration, not secure authentication. Credentials and application data are accessible to someone inspecting the browser.
- Data and images are saved in localStorage on the current browser and origin. Different devices, browsers, or URLs do not share data. Clearing site data removes saved changes.
- Notices and medical alerts update the demo data only; they do not send real notifications or contact emergency services.
- Browser storage has capacity limits. Large numbers of photos can exhaust it.
- Review all seeded names and contact details before public use. Do not enter real private student information in this demo.
- Real deployment requires server-side authentication, authorization, a shared database, and image storage.

## Future improvements

- Backend authentication and role-based authorization
- Shared database and file storage
- Split application code into maintainable modules
- Automated browser tests and accessibility review

## License

No open-source license has been selected yet. Add a license if you want to grant reuse permissions.
