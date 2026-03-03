# Reflection -- Hello, Azure AI

When I was staring I was thinking of how to categorize the request. I was thinking how to find the problem, where it is, and what category.

I at first had too many categories but fixed it after. I had to make sure the system message returned a JSON, because it was giving me errors when that wasn't in the prompt.

If the complaint is flagged, the harmful content should be removed but the message should still come though if it is a safety concern.

If we removed the content safety service, the model would still function but the content coming through would be unmoderated and could be offensive.

## 1. Service Surprises

I had some slight issues when trying to import packages but I just had the syntax wrong. I also had to make sure the method names were correct when accessing variables. I had to make sure the system message was clear when asking for a response and make sure the message was formatted in the way the model wanted.

## 2. Lazy Initialization

How I would explain would be that instead of putting keys into a file, you connect your azure account, and use those connections as variables to use with the api. It is more secure than having your keys in plaintext.

## 3. Content Safety in the Real World

Flag for human review and add the model's concerns. Perhaps the concern should pass be categorized first, then content moderation. Key phrase extraction should help with categorizing with human oversight.
