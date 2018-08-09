# Project Notes

***Note:** This document represents the specifics of this project as I understand them, and currently exists as a place for me to make sure they're written down somewhere. These details will likely all change with feedback and time.*

## Design

Points regarding style (colors, page themes, etc.) will be dealt with more at a later point, once the chart pages are more fully developed.

### Input

The JSON data file that will be available from an ARCC web server endpoint and is divided into different sections. Partition resources and total resources are listed, and five sections describe the queue of requests for resources from the perspectives of accounts, partitions, users, total resources, and quality of service.

### Output

A single web page that displays a chart of a section of resource data from the cluser, with controls to choose a different selection of resource data. Pie, donut, or sunburst variation charts are currently being considered.

### Infrastructure

No notes here at the moment.

## To Do

- [ ] Update data file formatting
- [ ] Set up Pages in repo for viewing from GitHub
- [ ] Add chart for Queue -> Users data
- [ ] Add chart for Queue -> Resourses (Total) data
- [ ] Add chart for Queue -> Partitions data (users on partitions?)
- [ ] Add chart for Queue -> QOS data
- [ ] Organize multiple charts on single scrolling page
- [ ] Find ways to switch between charts to eliminate scrolling
- [ ] Add more metadata presentation (breadcrumbs, legend)
- [ ] Look at showing just "running" requests (depending on context)
- [ ] Change slice colors to be more related, indicate structure

## Questions

*None at the moment.*
