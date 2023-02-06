<div style="height: 10vh; float: left; width: 85%; padding: 10px 100px 10px 100px; border: 1px dashed red;">
  <div style="position:absolute;
    top:0;
    left:0; display: flex; font-size: 24px; color: #42A5F5; text-align: left; border: 0px dashed blue;">
    <img height="40px" src="images/octo-white.png">&nbsp;&nbsp;&nbsp;<p>GitHub Professional Services - Applied Innersource (A Field Study)</p>
  </div>
</div>

<div style="height: 70vh; text-align: justify; font-size: 32px; float: left; width: 40%; padding: 10px 100px 10px 100px; border: 1px dashed red;">

### Issue Report

<img height="80%" src="images/issue-report-sample.png">
</div>  

<div style="height: 70vh; text-align: justify; font-size: 32px; float: left; width: 40%; padding: 10px 100px 10px 100px; border: 1px dashed red;">

### JSON Report

<pre><code style="max-height: 60vh" data-line-numbers="3,5,7,35,41,71,151,181">
{
    "meta": {
        "report_date": "Wed Feb 01 2023 18:26:03 GMT-0500 (Eastern Standard Time)",
        "fork": false,
        "org": "github-innersource",
        "repo": "an-innersource-repo",
        "owner": {
            "login": "github-innersource",
            "id": 110191229,
            "node_id": "O_kgDOBpFifQ",
            "avatar_url": "https://avatars.githubusercontent.com/u/110191229?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/github-innersource",
            "html_url": "https://github.com/github-innersource",
            "followers_url": "https://api.github.com/users/github-innersource/followers",
            "following_url": "https://api.github.com/users/github-innersource/following{/other_user}",
            "gists_url": "https://api.github.com/users/github-innersource/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/github-innersource/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/github-innersource/subscriptions",
            "organizations_url": "https://api.github.com/users/github-innersource/orgs",
            "repos_url": "https://api.github.com/users/github-innersource/repos",
            "events_url": "https://api.github.com/users/github-innersource/events{/privacy}",
            "received_events_url": "https://api.github.com/users/github-innersource/received_events",
            "type": "Organization",
            "site_admin": false
        },
        "full_name": "github-innersource/an-innersource-repo",
        "languages": {
            "JavaScript": 22,
            "Shell": 13
        }
    },
    "description": "Report for Innersource compliance.\nTo re-run this report use the **slash command:** `/check`\n\n",
    "license": {
        "name": "ISC License",
        "key": "isc",
        "spdx_id": "ISC",
        "compliant": true
    },
    "files": [
        {
            "name": "CODE_OF_CONDUCT.md",
            "compliant": false
        },
        {
            "name": "CODEOWNERS",
            "compliant": true
        },
        {
            "name": "CONTRIBUTING.md",
            "compliant": true
        },
        {
            "name": "README.md",
            "compliant": true
        },
        {
            "name": "CITATION.md",
            "compliant": false
        },
        {
            "name": "SUPPORT.md",
            "compliant": false
        },
        {
            "name": "SECURITY.md",
            "compliant": false
        }
    ],
    "branch_protection": [
        {
            "name": "allowsDeletions",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "allowsForcePushes",
            "value": false,
            "expected": false,
            "compliant": true
        },
        {
            "name": "isAdminEnforced",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "requiresApprovingReviews",
            "value": true,
            "expected": true,
            "compliant": true
        },
        {
            "name": "requiredApprovingReviewCount",
            "value": 1,
            "expected": 2,
            "compliant": false
        },
        {
            "name": "requiresCodeOwnerReviews",
            "value": true,
            "expected": true,
            "compliant": true
        },
        {
            "name": "requiresCommitSignatures",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "requiresConversationResolution",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "requiresLinearHistory",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "requiresStatusChecks",
            "value": true,
            "expected": true,
            "compliant": true
        },
        {
            "name": "requiresStrictStatusChecks",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "restrictsPushes",
            "value": false,
            "expected": true,
            "compliant": false
        },
        {
            "name": "restrictsReviewDismissals",
            "value": false,
            "expected": true,
            "compliant": false
        }
    ],
    "dependabot_alert_check": [
        {
            "package": "jquery",
            "severity": "MODERATE",
            "classification": "GENERAL",
            "name": "Cross-Site Scripting (XSS) in jquery [MODERATE]",
            "compliant": true
        },
        {
            "package": "jquery",
            "severity": "MODERATE",
            "classification": "GENERAL",
            "name": "XSS in jQuery as used in Drupal, Backdrop CMS, and other products [MODERATE]",
            "compliant": true
        },
        {
            "package": "jquery",
            "severity": "MODERATE",
            "classification": "GENERAL",
            "name": "Potential XSS vulnerability in jQuery [MODERATE]",
            "compliant": true
        },
        {
            "package": "jquery",
            "severity": "MODERATE",
            "classification": "GENERAL",
            "name": "Potential XSS vulnerability in jQuery [MODERATE]",
            "compliant": true
        }
    ],
    "health": 48
}
</code></pre>

</div>  

<!-- &#8681; -->

<!-- Add some speaker notes -->
Note: 
