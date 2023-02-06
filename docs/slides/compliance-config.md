<div style="height: 10vh; float: left; width: 85%; padding: 10px 100px 10px 100px; border: 0px dashed red;">
  <div style="position:absolute;
    top:0;
    left:0; display: flex; font-size: 24px; color: #42A5F5; text-align: left; border: 0px dashed blue;">
    <img height="40px" src="images/octo-white.png">&nbsp;&nbsp;&nbsp;<p>GitHub Professional Services - Applied Innersource (A Field Study)</p>
  </div>
</div>

<div style="height: 90vh; text-align: justify; font-size: 32px; float: left; width: 40%; padding: 10px 100px 10px 100px; border: 0px dashed red;">

## Policy Configuration

The configuratin Yaml contains 4 main categories
<br><br>
|||
|---|---|
|License| a list of accepted licenses|
|Files| a list of required files|
|Branch-Protection| expected Branch-Protection rules|
|Vulnerability Alert Threshold| alert >= severity = failed|

</div>  

<div style="color: black; height: 90vh; text-align: justify; font-size: 32px; float: left; width: 40%; padding: 10px 0px 10px 100px; border: 0px dashed green;">
<br><br>
<pre><code style="max-height: 80vh" data-line-numbers="3,7,16,32">
# Required License Types
license: 
  - MIT
  - ISC
# Required Innersource files
files:
  - CODE_OF_CONDUCT.md
  - CODEOWNERS
  - CONTRIBUTING.md
  - README.md
  - CITATION.md
  - SUPPORT.md
  - SECURITY.md
# Branch protection rules
branch_protection_rules: 
  allowsDeletions: true
  allowsForcePushes: false
  isAdminEnforced: true
  requiresApprovingReviews: true
  requiredApprovingReviewCount: 2
  requiresCodeOwnerReviews: true
  requiresCommitSignatures: true
  requiresConversationResolution: true
  requiresLinearHistory: true
  requiresStatusChecks: true
  requiresStrictStatusChecks: true
  restrictsPushes: true
  restrictsReviewDismissals: true
# Check on open Dependabot Alerts and verify the threshold
# Can be: low, medium, high, critical
dependabot_alert_threshold: high
</code></pre>
</div>  

&#x2003;
<!-- &#8681; -->

<!-- Add some speaker notes -->
Note: 
