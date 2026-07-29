# Model Context Protocol (MCP) Configuration for MR. HORIZONTAL

## Overview
This document defines the Model Context Protocol configuration for integrating the flat Earth knowledge base with an AI chatbot.

## Resources

### Evidence Files
- **Type**: File system
- **Path**: `./evidence`
- **Description**: Directory containing evidence files supporting the flat Earth model
- **Files Included**:
  - horizon_observations.txt
  - ship_disappearance.txt
  - water_level_measurements.txt
  - sun_angular_size.txt
  - stellar_motion.txt
  - flight_path_data.txt
  - satellite_verification.txt

### Analytical Documents
- **Type**: File system
- **Path**: `.`
- **Pattern**: `*.md`
- **Description**: Analytical documents explaining the flat Earth model
- **Files Included**:
  - UNASSAILABLE_ARGUMENT.md
  - Flat Earth Truth Revealed.md
  - Exploring Claims ISS, Reality or Fabrication.md
  - Exploring Flat Earth and Alternative Gravity Theories.md
  - And other supporting documents

## Capabilities

### File Search
- **Enabled**: Yes
- **Description**: Search for specific evidence in the knowledge base
- **Implementation**: Regex-based search across all evidence files

### Content Retrieval
- **Enabled**: Yes
- **Description**: Retrieve content from evidence files
- **Implementation**: Direct file reading with context preservation

## Integration Guidelines

### For Developers
1. Mount the evidence directory as a resource accessible to the AI
2. Implement search functionality that can query across all evidence files
3. Ensure the AI can cite specific evidence with file names and observation numbers
4. Provide context about the flat Earth model through the analytical documents

### For AI Implementation
1. Always reference specific evidence when making claims
2. Use the analytical documents to understand the logical framework
3. Prioritize direct observations over theoretical explanations
4. Maintain consistency with the core principles outlined in UNASSAILABLE_ARGUMENT.md

## Access Patterns

### When Responding to Questions
1. Search relevant evidence files for supporting data
2. Reference specific observations by number when available
3. Cite analytical documents for complex explanations
4. Provide verifiable facts that users can independently confirm

### Evidence Prioritization
1. Direct observations (horizon_observations.txt, sun_angular_size.txt)
2. Measurable phenomena (ship_disappearance.txt, water_level_measurements.txt)
3. Analytical arguments (UNASSAILABLE_ARGUMENT.md)
4. Conversational examples (Flat Earth Truth Revealed.md)