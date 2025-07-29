# Topic & Outline: Firebase — Full-stack Development with Auth, Firestore, Functions & Admin SDK

**I. Introduction**

- Overview of Firebase and Its Ecosystem
- Key products used: Auth, Firestore, Functions
- Why firebase ? compare with normal stack (server BE & FE)

**II. Firebase Auth (Client + Server)**

- Implement client login with Auth (Email Password Authentication / Sign in with Google/Facebook/Apple)
- Intro & demo features Firebase Admin SDK:
    - Manage & import users ??
    - ID token verify
    - Custom user claims
- Test with Firebase Local Emulator Suite

**III. Cloud Firestore**

- Intro Document-based structure and How to manage data
- Read data: query & limit & order & get real-time updates
- Implement Security rules & secure data access for users & groups
- Test with Firebase Local Emulator Suite
- Intro Backups & Point-in-time Recovery

**IV. Cloud Functions**

- Write & Test & Debug functions
- Integrate with other firebase services:
    - Authentication Triggers
    - Cloud Firestore Triggers
- Deploy functions

**V. Demo & Project Setup**

- Vite/React (client) + Node/Express (server)
- Full login → Firestore → cloud functions demo

→

Nhìn chung anh thấy ổn, tuy nhiên anh muốn bổ sung một phần là so sánh với stack bình thường và phân tích một số tiêu chí để chọn stack này cho project.

Về required attendees anh nghĩ là all web devs. Dù có phần Functions nó dính NodeJS nhưng cũng đơn giản, các bạn biết JS thì cũng có thể hiểu thôi.