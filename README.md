# B612 Asteroid Institute Contributor License Agreements Repository

This repository contains the digital signatures of B612 Asteroid Institute Contributor License Agreements.

## How to sign

Fork this repository, and then:
1. Using the GitHub web user interface, create a new file named `submissions/$USERNAME.md` (where `$USERNAME` is your GitHub username), containing **EXACTLY** the following text:
```
I, <MY NAME>, the author of this commit, hereby agree to the "B612 Asteroid Institute Entity Contributor 
License Agreement" as given in the CLA-INDIVIDUAL.md file included in this repository.
```
where `<MY NAME>` must be replaced by your legal name.

2. Submit a pull request with that change.

Note: It is important that you create the file using GitHub's web interface. That way, your commit will be signed by GitHub's GPG digital signature key, verifying it it was you who created the commit.

## FAQ

### Why do you ask contributors to sign the agreement?
We need to make sure that we, as well as the users of our software, are legally permitted to distribute your contributed code.

### What does this agreement cover?
It covers your contributions to all B612 projects. For example, if you've signed this agreement to contribute to ADAM, there's no need to re-sign it to contribute to a different B612 project in the future.

### How can you prove it was me who signed the CLA?
When a commit is created using GitHub's web interface, GitHub:
* Uses your name and the verified e-mail address for the commit Author field, and
* Digitally signs the entire commit with its own GPG key ([4AEE18F83AFDEB23](https://github.com/web-flow.gpg)).

This establishes to a high degree of certainty that the person who submitted the CLA signature is the same person who controls the GitHub account associated with the e-mail address listed in the commit 'Author' field.

This also why we require the CLA signatures be submitted using GitHub's web user interface.
