# Afternoon Pair Programming Project Time Checklist

Performed by Section Lead or designated PM in each section each afternoon:

- [ ] Drop link to Zoom created with section Zoom account.
- [ ] Add other section PMs as co-hosts.
- [ ] Announce the project and review the README with the class.
- [ ] Review how to fork and add a collaborator to the forked repository.
	- [ ] Person A forks the Lambda School repository.
		![Only one person needs to fork the Lambda School repository](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/fork.png)

	- [ ] Person A adds person B as a Collaborator.
		![Add your partner as a collaborator](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/add-collaborator.png)

	- [ ] Person B accepts invite. The invite will be e-mailed to the e-mail account person B used to register with GitHub
	- [ ] _**Both**_ clone person A’s repository: `git clone {person A's URL}`. For example:
		![Copy the repository URL from GitHub](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/copy-url.png)

```console
$ git clone https://github.com/mixelpixel/Precourse.git
	Cloning into 'Precourse'...
	remote: Counting objects: 36, done.
	remote: Compressing objects: 100% (35/35), done.
	remote: Total 36 (delta 8), reused 1 (delta 0), pack-reused 0
	Unpacking objects: 100% (36/36), done.
$ cd Precourse/
$ git remote -v
	origin	https://github.com/mixelpixel/Precourse.git (fetch)
	origin	https://github.com/mixelpixel/Precourse.git (push)
```

- [ ] Review pair programming best practices.
	- [ ] One student "drives" (does the typing), and the other "navigates."
	- [ ] Make Git commits _often_.
	- [ ] Switch roles every 30 minutes.
	- [ ] Upon the first switch, make a Pull Request to Lambda School.
		![Make a NEW Pull Request](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/new-Pull-Request.png)
		![COMPARE the new Pull Request changes](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/compare-Pull-Request-changes.png)
		![Open the new Pull Request](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/open-Pull-Request.png)
		![EDIT the Pull Request](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/edit-PR-title.png)
		![SAVE the Pull Request title change](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/save-PR-title-change.png)
		![BOTH full names in the Pull Request title](https://github.com/LambdaSchool/Instruction-Checklists/raw/master/img/both-full-names-in-PR-title.png)

	- [ ] With every switch, push and pull all changes. They will get added to the Pull Request automatically.
- [ ] Create breakout sessions to randomly assign pairs.
- [ ] PMs use the breakout rooms to drop in and help groups with questions.
- [ ] Send switch reminders every 30 minutes ([on the half hour](https://en.wiktionary.org/wiki/on_the_half_hour)).
- [ ] PMs leave feedback on students' Pull Requests: [https://github.com/LambdaSchool/Code-Review-Checklist](https://github.com/LambdaSchool/Code-Review-Checklist)
