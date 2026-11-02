# Source SBOM

**Initial source snapshot, not a release report.** Source commit `8e264d243bbd4467bd19f3f28292219405b47e0e` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/deepcw-engine `8e264d243bbd4467bd19f3f28292219405b47e0e`

- sbom:role: source-root
- sbom:git-commit: 8e264d243bbd4467bd19f3f28292219405b47e0e
- sbom:git-tree: 932ebccd6650eaea37a964380755ae4420244725
- sbom:source-repository: https://github.com/wave-owl/deepcw-engine
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "0d96a4ff68ad6d4b6f1f30f713b18d5184912ba8dd389f86aa7710db079abcb0"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/deepcw-engine | 8e264d243bbd4467bd19f3f28292219405b47e0e | source-root | unresolved; manual review required |
| model.onnx | unresolved | model-file | unresolved |
| model.onnx.json | unresolved | model-file | unresolved |
| Conditional source requirements declared by examples/nodejs/package.json | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/python/requirements.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| examples/python/requirements.txt: numpy>=1.24, onnxruntime>=1.17 | unresolved | conditional-build-runtime-requirement | unresolved |
| examples/nodejs/package.json: onnxruntime-node ^1.18.0; no package-lock.json found | unresolved | conditional-build-runtime-requirement | unresolved |
| adm-zip | 0.5.17 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| deepcw-onnx-nodejs-example | 1.0.0 | Syft source/package discovery | [{"license": {"id": "AGPL-3.0-only"}}] |
| define-data-property | 1.1.4 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| define-properties | 1.2.1 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| es-define-property | 1.0.1 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| es-errors | 1.3.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| escape-string-regexp | 4.0.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| global-agent | 4.1.3 | Syft source/package discovery | [{"license": {"id": "BSD-3-Clause"}}] |
| globalthis | 1.0.4 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| gopd | 1.2.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| has-property-descriptors | 1.0.2 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| matcher | 4.0.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| object-keys | 1.1.1 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| onnxruntime-common | 1.26.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| onnxruntime-node | 1.26.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| semver | 7.8.4 | Syft source/package discovery | [{"license": {"id": "ISC"}}] |
| serialize-error | 8.1.0 | Syft source/package discovery | [{"license": {"id": "MIT"}}] |
| type-fest | 0.20.2 | Syft source/package discovery | [{"expression": "MIT OR CC0-1.0"}] |
| examples/nodejs/package-lock.json | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
