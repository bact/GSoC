# 2025 projects

## SBOM conformance checker

Create a web accessible tool for validating SPDX 3.0 documents.

An online form which allows the uploading, parsing, and validation of SPDX 3.0
would provide immediate benefit to the SPDX community.
There is no specific programming language requirement, but there is an existing
Java and Python libraries which could be used in the project.
Some of the technical challenges for this project include having to handle long
running operations and implementing a very robust parser implementation able to
handle any input.

### Size

Medium (175 hours)

### Level of difficulty

Hard

### Skills needed

- Software development skills for web-based applications
- Good user interface design skills
- Understanding of SBOM conformance and related standards/regulations such has
  CISA Common Software Bill of Materials or EU AI Act

### Mentors

John Speed Meyers, Gary O'Neall

### GSoC link

- <https://summerofcode.withgoogle.com/programs/2025/projects/CeR3hQTq>

## Enhancing the functionality of spdx-license-diff

The spdx-license-diff tool is a JavaScript-based web browser plugin that
enables users to easily compare license text on a website with the contents of
all licenses on the SPDX License List, generating percentage matches and
differences.

spdx-license-diff requires updates to enable it to continue working with newer
versions of Firefox and Chrome –
see <https://github.com/spdx/spdx-license-diff/issues/121> and
<https://github.com/spdx/spdx-license-diff/issues/122> for example.

There are also several areas where its functionality could be extended, such as:

- More fully implementing the SPDX License List Matching Guidelines when
  performing matches
- Indicating which of several “alt” options for regular expressions is matched
- Other usability and functionality improvements

### Size

Medium (175 hours)

### Level of difficulty

Medium

### Skills needed

- Software development skills for Browser extensions
- Good user interface design skills
- Proficient in Javascript

### Mentors

Vedant Jolly, Rohit Lodha, Gary O'Neall

### GSoC Link

- <https://summerofcode.withgoogle.com/programs/2025/projects/TwtGeZ4X>
