# Repo security

## Overview

This document describes steps taken by the School of Information IT team to improve the security of repos hosted in the UC Berkeley School of Information GitHub org.  

A general discussion of GitHub repo security is beyond the scope of this document.  Anyone wishing to learn more about GitHub security may find GitHub's own documentation helpful:

* [Administering a repository](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository): See especially "[Securing your repository](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/securing-your-repository)"
* [Managing Security Vulnerabilities](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities)

## Public vs Private repos

By default, repos created in this GitHub org are private.  Only org members who have been granted the necessary permissions can view or modify the contents of a private repository.

Public repos are accessible to anyone on the internet, so only org administrators can make a private repo public.  If you want to make a repo public, please contact your instructor or the School's IT team.

Please note that the School of Information IT team reserves the right to remove public access from any repo that violates the policies defined in this repo.

## Keep secrets out of GitHub repos.

The biggest risk of making repos public is the accidental disclosure of sensitive information, such as:

* Personally identifiable information
* Credentials that grant access to other systems, especially if that system is tied to your credit card.

Please note that GitHub is a [version control](https://en.wikipedia.org/wiki/Version_control) system.  Any content that you have ever committed to your GitHub repo is still in your repo, even after you have deleted it.  There are a number of publicly accessible tools designed to find sensitive information in your GitHub history, so if you have ever committed sensitive info to a GitHub repo, don't make it public. 

Please also note that the School of Information IT team reserves the right to remove public access from any repo where we have a confirmed leak of personal data or credentials that grant access to other systems.
