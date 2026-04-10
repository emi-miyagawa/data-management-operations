## Focus Areas

- Field definition and naming consistency (e.g., avoiding duplicate meanings such as "customer_id" vs "client_id")
- Required vs optional field design to balance completeness and usability
- Data validation rules (format, completeness, duplication checks)
- Exception handling for incomplete or inconsistent data
- Input standardization for non-technical users (e.g., dropdowns, templates)
- Workflow checkpoints to prevent downstream errors

## Example: Address Data Handling

### Problem
Address data was often incomplete (missing street number, incorrect format), leading to undeliverable mail and operational waste.

### Approach
- Defined required vs optional fields
- Added validation checks for missing components
- Flagged high-risk records before processing

### Result
- Reduced undeliverable cases (~50% estimated)
- Reduced manual correction workload

### Trade-offs
- Could not fully validate all edge cases
- Required manual confirmation for ambiguous records
