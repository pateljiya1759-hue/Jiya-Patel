📱 What Has Been Built
🎭 Multi-Category Activity Management

Cultural Activities: Music fests, dance battles, street plays, open mics, and art expos.
Sports & Athletics: Inter-department cricket, football turf league, badminton, and campus marathons.
Clubs & Societies: Tech chapters (Robotics & AI), Rotaract volunteering, literary societies, and debate leagues.
Workshops & Academics: Edge AI bootcamps, UI/UX sprints, and blood donation drives.
Detail screens with rules, schedules, venue, seats remaining, and coordinator contacts.
📊 Student Activity Portfolio & Transcripts

Graduation Credit Progress: Tracks earned extracurricular points against degree requirements (e.g., 75/100 credits).
Category Breakdown: Separate point tallies for Cultural, Sports, Clubs, and Volunteering.
Formal Activity Transcript: Accredited non-academic transcript complete with institutional seal, ready for job placements, audits, and higher studies.
📲 QR Attendance & Check-In Verification

Digital Event Passes: Instant QR pass generated upon activity enrollment.
Coordinator Scanner & Verifier: Event leads and faculty scan student QR tokens at the venue to verify attendance on the spot and disburse points.
🏆 Cryptographic Digital Certificates

Automatic generation of verified participation and achievement certificates featuring serial codes, verification hashes, and Dean's digital sign-off.
👥 Club & Society Hub

Club directory with leadership contacts, meeting schedules, announcements feed, and 1-tap membership enrollment (+10 credits per active club).
🛠️ Admin & Faculty Portal

Analytics overview: Total active events, participation counts, and department engagement breakdown.
Event creation form to publish new activities with custom credit points.
Export student participation reports to accreditation-ready CSV format.
📁 Project Structure
text


C:\Users\patel\.gemini\antigravity\scratch\campus_activity_tracker/
├── lib/
│   ├── data/
│   │   ├── models/            # Data models
│   │   ├── repositories/      # CampusRepository (single source of truth)
│   │   └── services/          # MockCampusService (seed campus data)
│   ├── domain/
│   │   └── models/            # Activity, Student, Club, Participation, Certificate
│   ├── ui/
│   │   ├── core/              # Theme, Badges, QR Mock Painter, Stat Cards
│   │   └── features/
│   │       ├── activities/    # Activity lists, search, category filters & details
│   │       ├── clubs/         # Club directory, announcements & join/leave
│   │       ├── portfolio/     # Student report, credit meter & formal transcript
│   │       ├── attendance/    # QR passes, coordinator check-in & certificates
│   │       ├── admin/         # Faculty dashboard, event publishing & CSV export
│   │       └── home/          # Home navigation shell with Student/Admin toggle
│   └── main.dart              # Application entrypoint
├── test/
│   └── campus_repository_test.dart  # Automated test suite
└── pubspec.yaml
🚀 Running the Application
You can set C:\Users\patel\.gemini\antigravity\scratch\campus_activity_tracker as your active workspace and run:

bash


# 1. Navigate to the project directory
cd "C:\Users\patel\.gemini\antigravity\scratch\campus_activity_tracker"
# 2. Fetch Flutter packages
flutter pub get
# 3. Launch on Chrome (web) or your connected Android/iOS device
flutter run -d chrome
# 4. Run automated test suite
flutter test
8:44 AM
