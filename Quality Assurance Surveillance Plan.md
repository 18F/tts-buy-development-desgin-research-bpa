**General Services Administration **

Federal Acquisition Service  
Technology Transformation Services

1800 F St NW | Washington, DC | 20006

TTS BPA for Software Development, Design, and Research

Quality Assurance Surveillance Plan

#   
Introduction

The Federal Acquisition Service (FAS, Technology Transformation Service
(TTS), Office of Acquisition (OA), has developed this Quality Assurance
Surveillance Plan (QASP) to evaluate contractor actions while
implementing the Performance Work Statement (PWS) at the order level. It
is designed to provide an effective surveillance method of monitoring
contractor performance for each listed objective on the Performance
Requirements Summary at the order level. It also provides a systematic
method to evaluate the services the contractor is required to furnish.

# 1.0 Standard

The contractor is responsible for management and quality control actions
to meet the terms of the agreement. The contractor shall perform all
work required in a satisfactory manner in accordance with the
requirements of the PWS. The COR shall notify the CO for appropriate
action if it is likely that the contractor will not achieve successful
final delivery of the software code in accordance with the performance
objectives and acceptable quality levels identified below.

# 2.0 The Contracting Officer

The contracting officer (CO) is responsible for monitoring contract
compliance, contract administration, cost control, and for resolving any
differences between the observations documented by the contracting
officer's representative (COR) and the contractor. The CO will designate
one full-time COR as the government authority for performance
management. The number of additional representatives serving as
technical inspectors depends on the complexity of the services measured,
as well as the contractor’s performance, and must be identified and
designated by the CO.

# 3.0 The Contracting Officer’s Representative

The contracting officer’s representative (COR) is designated in writing
by the CO to act as his or her authorized representative to assist in
administering a contract. COR limitations are contained in the written
appointment letter. The COR is responsible for technical administration
of the project and ensures proper government surveillance of the
contractor’s performance. The COR is not empowered to make any
contractual commitments or to authorize any contractual changes on the
government’s behalf. Any changes that the contractor deems may affect
contract price, terms, or conditions shall be referred to the CO for
action. The COR will have the responsibility for completing Quality
Assurance (QA) monitoring forms used to document the inspection and
evaluation of the contractor’s work performance. Government surveillance
may occur under the inspection of services clause for any service
relating to the contract.

# 4.0 Performance Requirements Summary

The COR will evaluate the performance objectives through surveillance as
reflected below by reviews and acceptance of work products and services.
As indicated, the COR will assess progress towards the final delivered
software code. Note that the performance requirements listed below are
required for the final deliverable. However, the sprints and incremental
delivery of code will be assessed by the government to ensure that the
contractor is on a path to  
successful final delivery.  
  
The following table sets forth the performance standards and quality
levels the code and documentation provided by the Contractor must meet,
and the methods the TTS will use at the order level to assess the
standard and quality levels of that code and documentation.

<table>
<thead>
<tr class="header">
<th><strong>Deliverable</strong></th>
<th><strong>Performance Standard(s)</strong></th>
<th><strong>Acceptable Quality Level</strong></th>
<th><strong>Method of Assessment</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Tested Code</td>
<td><p>Code delivered under the order must have substantial test code coverage and a clean code base</p>
<p>Version-controlled Court GitHub repository of code that comprises product that will remain in the government domain</p></td>
<td>Minimum of 90% test coverage of all code</td>
<td>Combination of manual review and automated testing</td>
</tr>
<tr class="even">
<td>Properly Styled Code</td>
<td><a href="https://frontend.18f.gov/#js-style">GSA 18F Front End Guide</a></td>
<td>0 linting errors and 0 warnings</td>
<td>Combination of manual review and automated testing</td>
</tr>
<tr class="odd">
<td>Accessible</td>
<td>Web Content Accessibility Guidelines 2.1 AA (WCAG 2.1 AA) standards</td>
<td>0 errors reported for WCAG 2.1 AA standards using an automated scanner and 0 errors reported in manual testing</td>
<td><a href="http://squizlabs.github.io/HTML_CodeSniffer/" class="uri">http://squizlabs.github.io/HTML_CodeSniffer/</a> or <a href="https://github.com/pa11y/pa11y" class="uri">https://github.com/pa11y/pa11y</a></td>
</tr>
<tr class="even">
<td>Deployed</td>
<td>Code must successfully build and deploy into staging environment.</td>
<td>Successful build with a single command</td>
<td>Combination of manual review and automated testing</td>
</tr>
<tr class="odd">
<td>Documentation</td>
<td>All dependencies are listed and the licenses are documented. Major functionality in the software/source code is documented. Individual methods are documented inline using comments that permit the use tools such as JsDoc. System diagram is provided.</td>
<td>Combination of manual review and automated testing, if available</td>
<td>Manual review</td>
</tr>
<tr class="even">
<td>Secure</td>
<td>OWASP Application Security Verification Standard 3.0</td>
<td>Code submitted must be free of medium- and high-level static and dynamic security vulnerabilities</td>
<td>Clean tests from a static testing SaaS (such as Gemnasium) and from OWASP ZAP, along with documentation explaining any false positives</td>
</tr>
<tr class="odd">
<td>User research</td>
<td>Usability testing and other user research methods must be conducted at regular intervals throughout the development process (not just at the beginning or end).</td>
<td>Research plans and artifacts from usability testing and/or other research methods with end users are available at the end of every applicable sprint, in accordance with the vendor’s research plan.</td>
<td>TTS will evaluate the artifacts based on a research plan provided by the vendor at the end of the second sprint and every applicable sprint thereafter.</td>
</tr>
</tbody>
</table>
