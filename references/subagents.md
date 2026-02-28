# Subagents

Computer can spawn parallel subagents to complete tasks faster and at greater scale.

## What subagents do

Subagents are parallel instances of Computer that work simultaneously on different parts of a task. The main agent orchestrates them and synthesizes their results.

## Use cases

### Batch processing
- Analyze 50 companies simultaneously
- Process 100 documents in parallel
- Generate 20 images at once

### Parallel research
- Research multiple topics at the same time
- Compare competitors by researching each in parallel
- Gather data from multiple sources simultaneously

### Large-scale automation
- Send personalized outreach to a list of contacts
- Extract data from many web pages in parallel
- Run the same analysis on multiple datasets

## How to trigger subagents

Users don't need to explicitly request subagents. Computer automatically uses them when a task involves:
- A list of items to process
- Multiple independent research threads
- Batch operations that benefit from parallelism

Users can also explicitly request: "Do this for each of these 30 companies in parallel."

## Limitations

- Subagents consume credits proportionally
- Each subagent has its own step budget
- Results are synthesized by the main agent, which may lose some detail
- Not all tasks benefit from parallelism
