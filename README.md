# ApiUsingRestCouchbaseLiteAndRxPOC

1. Created a Xamarin.Forms project (iOS and Android - removing the WinPhone project because Couchbase Lite does not yet support WinPhone (28 Feb 2015)).
2. Added the Shared Project ApiPOC.Shared
3. For both the ApiPOC.iOS and ApiPOC.Droid projects, added a reference to the shared project (by selecting References, right-clicking References and then selecting 'Add Shared Project Reference' and on the next screen, selecting the shared Project.)
4. Selected ApiPOC.Shared, right-clicked, selected Properties, and changed the Root Namespace to ApiPOC.
5. Add a Portable Class Library for TDD Testing, named ApiPOCTddTests.
6. Select the TDD project, right-click, select properties, and then remove the Windows projects that restrict adding NUnit to the project.
7. Add NUnit, using the Nuget Package Manager.
8. Add a TestFixture to the TDDF project called APITests.
9. Commit this initial setup to GitHub.
