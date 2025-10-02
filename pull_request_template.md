# Pull Request Checklist

Please make sure your PR meets the following requirements before requesting review:

- [ ] **Chart version updated**  
  - Updated `version` in `Chart.yaml` for each modified chart.  
  - Version follows **Semantic Versioning (SemVer)** (e.g., `1.2.3`).  

- [ ] **Tests pass locally**  
  - Ran `helm lint` on changed charts.  
  - Ran `helm template` to ensure manifests render correctly.  
  - Ran `bats` unit tests (if applicable).  

- [ ] **Documentation updated** (if applicable)  
  - README.md or values schema updated for new features, breaking changes, or config changes.  

- [ ] **Codeowners approval**  
  - Relevant chart owners listed in `CODEOWNERS` have been requested as reviewers.  

---

## Description

_Provide a brief description of the change. What problem does it solve, or what new capability does it add?_

---

## Related Issues

_Link any related issues_
