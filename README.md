My-Own-Mod-Mod-Pack-Launch
==========================

Feed The Beast Products
Look At This For The Real Products
 	.settings 	Also revert .settings/org.eclipse.jdt.core.prefs 	7 months ago
	res 	Merge pull request #617 from johnneijzen/patch-3 	8 days ago
	src 	add in support for 1.6.x packs in offline mode 	11 days ago
	.classpath 	Revert .classpath to upstream configuration. 	7 months ago
	.gitignore 	How'd that get in there? o.O 	a year ago
	.project 	Initial commit 	a year ago
	licenseheader.txt 	License headers added. 	a year ago
	pom.xml 	bump version for next dev cycle, upgrade permgen defaults on 1.6 + pa… 	14 days ago
	readme.md 	Cleaned up the pom.xml based on Maven standards. 	a year ago
	style_checks.xml 	Better configuration of Maven Checkstyle.
	And Heres The Theard Of It 
	<Copyrights Legal Website:https://github.com/Slowpoke101/FTBLaunch>
	And The Copyrights Is The Website And The Other Part Of The Theard
	FTB Launcher
The license

Copyright 2012 FTB Launcher Contributors

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
Compiling

    Download the source from this repo, either with git or as a zip/tarball.
    Install maven or Eclipse
    If using maven, run mvn in the directory you installed it to.
    With Eclipse, open as a project and build as usual

Pull Request Standards

    Indent with tabs
    Avoid trailing whitespace
    Sign-off your commits
    Avoid merge commits in pull requests
    Squash your commits - have at most one commit per major change

Updating your fork

Before submitting a pull request, you should ensure that your fork is up to date. To do this, run these commands:

git remote add upstream git://github.com/Slowpoke101/FTBLaunch.git
git pull --rebase upstream master
git push --force origin <branch_name>

The first command is only necessary the first time. If you have issues merging, you will need to get a merge tool such as P4Merge. Once it is set up, run git mergetool. Once all conflicts are fixed, run git rebase --continue, and git push --force origin <branch_name>.
Yeah So Yeah Now You Get It Its Minecraft FTB Copyrighs resavred commmand /1/ COPY RIGHTS COPYRIGHTS ..... YeahhhH!!!
