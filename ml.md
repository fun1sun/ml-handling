<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Manual Letter Handling in Healthbuzz</title>
<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
  }
  h1 {
    color: #2c3e50;
    text-align: center;
  }
  .section {
    background: #fff;
    margin-bottom: 10px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  .section-header {
    background-color: #2980b9;
    color: #fff;
    padding: 15px;
    cursor: pointer;
    font-weight: bold;
    border-radius: 8px 8px 0 0;
  }
  .section-content {
    display: none;
    padding: 15px;
  }
  ul {
    padding-left: 20px;
  }
  li {
    margin-bottom: 8px;
  }
  /* Toggle arrow indicator */
  .arrow {
    float: right;
    transition: transform 0.3s ease;
  }
  .active .arrow {
    transform: rotate(90deg);
  }
</style>
</head>
<body>

<h1>Manual Letter Handling in Healthbuzz</h1>

<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    1. Letter Types <span class="arrow">▶</span>
  </div>
  <div class="section-content">
    <h3>1.1 Standard Reject & Rescind</h3>
    <ul>
      <li>Reject (Standard, Manual)</li>
      <li>Stand-firm Reject</li>
      <li>Rescind (Initial, Reverse)</li>
      <li>Hospital Reject (Various specific cases)</li>
      <li>No CFII / No OR / After Grace Period / Non-defined Mainland HK</li>
    </ul>
    <h3>1.2 Counteroffer & Endorsement</h3>
    <ul>
      <li>Counteroffer (Initial, Reverse)</li>
      <li>Endorsement</li>
    </ul>
    <h3>1.3 Apology & Special Consideration</h3>
    <ul>
      <li>Apology (with claw back, deduct future claim, other issues)</li>
      <li>Special consideration / Ex-gratia payment</li>
    </ul>
    <h3>1.4 Others</h3>
    <ul>
      <li>Close File / Investigation</li>
      <li>Explain Issue / CTC / Destroy / Claim Decision</li>
      <li>Manual Settlement / Status / Refund Covering</li>
      <li>Post-audit / Reissue Cheque / Autopay rejection</li>
    </ul>
  </div>
</div>

<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    2. Letter Templates & Display <span class="arrow">▶</span>
  </div>
  <div class="section-content">
    <h3>2.1 Classification</h3>
    <ul>
      <li>Based on letter type (Reject, Rescind, Counteroffer, Apology, etc.)</li>
      <li>Specific templates for different scenarios</li>
    </ul>
    <h3>2.2 Variants</h3>
    <ul>
      <li>Standard, Manual, Stand-firm, Hospital-specific, CHI version, etc.</li>
    </ul>
    <h3>2.3 Additional Functionality</h3>
    <ul>
      <li>Create flags/boxes for "Manual Letter"</li>
      <li>View existing/manual draft letters</li>
      <li>Automatic population of customer data</li>
    </ul>
  </div>
</div>

<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    3. Manual Letter Handling Process <span class="arrow">▶</span>
  </div>
  <div class="section-content">
    <h3>3.1 Claim Assessment & Decision</h3>
    <ul>
      <li>Claim decision in EWS (Approve, Reject, Cancel)</li>
      <li>System auto-uploads in AWD at 10 PM daily</li>
    </ul>
    <h3>3.2 Manual Letter Drafting & Review</h3>
    <ul>
      <li>Selection of templates</li>
      <li>Drafting and saving letters</li>
      <li>Cross-checking by claim approvers</li>
      <li>Re-assigning claims for manual review</li>
    </ul>
    <h3>3.3 Finalization & Dispatch</h3>
    <ul>
      <li>Approval of manual letters</li>
      <li>Automatic upload to AWD</li>
      <li>Printing, passing to vendor, and mailing</li>
      <li>Customer receipt</li>
    </ul>
  </div>
</div>

<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    4. System Features & Reports <span class="arrow">▶</span>
  </div>
  <div class="section-content">
    <h3>4.1 System Flags & Buttons</h3>
    <ul>
      <li>Manual Letter flag</li>
      <li>Draft / View existing manual letter buttons</li>
      <li>Cross-check & approval pop-ups</li>
    </ul>
    <h3>4.2 Monitoring & Reporting</h3>
    <ul>
      <li>Turnaround Time (TAT) report</li>
      <li>Data required for monitoring process efficiency</li>
    </ul>
  </div>
</div>

<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    5. Additional Notes <span class="arrow">▶</span>
  </div>
  <div class="section-content">
    <ul>
      <li>Process flow after claim completion</li>
      <li>Handling different claim decision scenarios</li>
      <li>System automation and manual interventions</li>
    </ul>
  </div>
</div>

<script>
  function toggleSection(element) {
    const section = element.nextElementSibling;
    section.style.display = section.style.display === "block" ? "none" : "block";
    element.classList.toggle("active");
  }
</script>

</body>
</html>
