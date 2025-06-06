# AgentplusAddinskill

Repo for DA plus addinskill sample: citation management for Word document.

## Supported Actions

1. **Insert a citation/reference** into the current document selection. The reference can be retrieved from a web search based on its title.
2. **Update a citation/reference** based on its index and a new reference, which can also be retrieved from a web search based on its title.
3. **Remove a citation/reference** related to its index.

## Implementation Details

- The citation/reference is implemented by leveraging **ContentControl** in Word. See the code for more details.
- Only two citation types are supported in this sample:
  - `"IEEE"`
  - `"Vancouver"`

> Note: It can be extended to support more citation types if needed.
