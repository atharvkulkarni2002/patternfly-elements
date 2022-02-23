# @patternfly/pfe-codeblock

## 2.0.0-next.0
### Major Changes

- 04f98667: ## 🔥 Migrate to Lit
  
  This release migrates `<pfe-codeblock>` to LitElement.
  
  ### NEW: CSS Shadow Parts!
  - Adds `pre` and `code` CSS parts
  
  ### Breaking Changes
  - Initial render is now [asynchronous](https://lit.dev/docs/components/lifecycle/#reactive-update-cycle).
    If your code assumes that shadow DOM is ready once the element is constructed, update it to `await element.updateComplete`
  
  
  See [docs](https://patternflyelements.org/components/codeblock/) for more info

### Patch Changes

- Updated dependencies [e8788c72]
  - @patternfly/pfe-core@2.0.0-next.0