# Property workflow design

I’m developing an internal tool for property management. I design the workflows and data relationships, including which decisions need someone’s approval. AI coding tools handle most of the coding and integration.

## A fictional repair request

A tenant emails about a leaking tap. The proposed workflow classifies the email as a repair request and uses it to start coordination. Approval and completion each need their own record. Later, posting an approved repair invoice records an expense and an amount owed to the supplier. A payment needs separate confirmation. Keeping those steps distinct lets a colleague answer two everyday questions: “Is the tap fixed?” and “Has the supplier been paid?”

To evaluate the workflow, I would follow a sample of requests from email through closure, check who owned each next action, and compare handling time and missed follow-ups with the existing process.

