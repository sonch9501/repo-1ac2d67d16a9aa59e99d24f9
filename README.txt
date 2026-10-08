Azure Logic Apps Consumption: Azure DevOps work item creation sample

workflow.json contains the supplied workflow with only the DueDate expression changed.
DueDate uses the next calendar date in Japan (Tokyo Standard Time / UTC+09:00), formatted as yyyy-MM-dd.
Expression reference: https://learn.microsoft.com/en-us/azure/logic-apps/expression-functions-reference

Replace YOUR_ORGANIZATION and YOUR_PROJECT for your environment.
YOUR_PAT is a placeholder; supply the real PAT securely at deployment and never commit it.
The work item type, custom fields, allowed values, and permissions must match the target project.
JSON parsing and Japan-date boundary examples were checked locally.
Not deployed or executed against Azure; no end-to-end validation has been performed.
