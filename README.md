Usage
=====
    
    usage: github2jira [-h] [--repo REPO] [--user USER] [--project PROJECT]
                       [--githubbaseurl GITHUBURL] [--jirabaseurl JIRAURL]
                       ISSUE [ISSUE ...]
    
    Convert GitHub issue into JIRA issue
    
    positional arguments:
      ISSUE                 The issue number
    
    optional arguments:
      -h, --help            show this help message and exit
      --repo REPO           The name of the repository (default:
                            EnMasseProject/enmasse)
      --user USER           The name of the user in the JIRA system
      --project PROJECT     The project in the JIRA system (default: ENTMQMAAS)
      --githubbaseurl GITHUBURL
                            The base URL for github (default:
                            https://api.github.com)
      --jirabaseurl JIRAURL
                            The base URL for jira (default:
                            https://issues.jboss.org/rest/api/2)
