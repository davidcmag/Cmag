# SMTP 0.12.2: qualify Mac test socket calls

Fixes the reported Mac test compile error where bind resolved to an inherited
NSObject/XCTest method. Uses Darwin.bind and qualifies the other Mac fixture
socket functions. The TLS status correction from 0.12.1 is retained.

176 portable tests pass; actual corrected Mac tests remain unrun.
Open EmailGrabber3.xcodeproj directly to compile in Xcode. Terminal verification
is an optional separate workflow, not a prerequisite for opening the project.
In Xcode choose EmailGrabber3 / My Mac: Command-B builds, Command-U tests,
Command-R runs. Keep the prior app and saved-data backup.

Archive SHA256: `720376ca074d56a979c8269f92246f313a7ff80d8e0f7ec93d04c7835ba707dc`
