start->router->research->orchestrator->worker->reducer->end

1. start: initial message mentioning topic is given
2. router: it decides whether to send it to orchestrator or research(only when web searching is required for recent topics) depending on the requirement
3. research: surfs online on different websites using tavily.
4. orchestrator: planner node that generates plan and sections in blogs.
5. worker: no. of sections=no. of worker nodes, working on respective sections parallely.
6. reducer: stitches all sections ,give combined blog to llm , finds out where images are required and asks to add image.
7. end
