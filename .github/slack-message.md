🚨 *Conflict Alert!*
👤 <@${{ fromJson(steps.read_slack_map.outputs.map)[steps.pr_creator.outputs.pr_creator] }}>, your PR to *main* caused a conflict with *develop*.
⚡ *Action needed*: Please resolve it ASAP! 🚀
🔗 *PR link*: <${{ github.event.pull_request.html_url }}|Click here to view your PR>

👉 *How to fix it:*
• Checkout `develop`, pull latest
• Create branch `resolve-conflict`
• Merge `main` into it
• Resolve conflicts, commit, push
• Open PR from `resolve-conflict` to `develop`
