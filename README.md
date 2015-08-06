# multiplaid
Cross-platform native Slack client that supports multi-channel views

This project is in no way supported by or affiliated with Slack Technologies, Inc.

The purpose of this project is to build a cross-platform, native Slack client in Python (3.4), using PyQt's Qt5 bindings.

Goals:

* Allow multiple channels to be open simultaneously -- track multiple conversations without constant channel switching and notification overload
* Provide dark theme / night mode out of the box
* Entire interface themable via css or similar
* Minimal interace cruft, such as the Slack sidebar, so as to maximize channel conversation space
* Serve as test-bed and core classes for a terminal based Slack client. (I want to be able to ssh into a remote machine and Slack-share a file directly from the commandline, or download a file that was shared on Slack directly to the remote.)
