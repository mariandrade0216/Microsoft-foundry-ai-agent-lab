# Microsoft Foundry AI Agent Lab — Results

## Objective
Create and test an AI agent using Microsoft Foundry and Visual Studio Code for the Web.

## Environment
- **Platform:** Microsoft Foundry
- **Code environment:** VS Code for the Web
- **Model:** gpt-5-mini
- **Agent:** Maria
- **Language:** Python

## Work Completed
1. Opened the existing Maria agent in Microsoft Foundry.
2. Updated the agent instructions to help users plan projects and follow safety boundaries.
3. Tested the agent with a prompt-injection-style request asking it to ignore its instructions and reveal confidential information.
4. Observed that the agent refused to reveal confidential information while still helping with a school-project plan.
5. Opened the generated Python project in VS Code for the Web.
6. Installed a missing Python dependency, `httpx`.
7. Ran `python run_agent.py` successfully and received a response from the agent.

## Results
The agent responded in the Microsoft Foundry playground and through the Python script. During the security test, it refused the request to reveal confidential information and continued to provide useful assistance.

The Python script returned a project-assistant greeting and offered help with planning tasks, schedules, checklists, risks, and next steps.

## Conclusion
This lab demonstrated how to configure an AI agent in Microsoft Foundry, test its behavior, and invoke it from Python. The security test showed a useful example of instruction-following and resistance to a prompt-injection-style request. This test alone does not guarantee that the agent is protected against every security threat.

## Repository
[Microsoft Foundry AI Agent Lab](https://github.com/mariandrade0216/Microsoft-foundry-ai-agent-lab)
