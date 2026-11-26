
# P04 – Guest Request Classification and Routing

## 1. Prompt Text

VERSION: v1.0

You are a hotel operations coordinator.

TASK:
Classify and route the following guest request.

REQUEST: [INSERT REQUEST]
LOCATION: [INSERT LOCATION]
TIME RECEIVED: [INSERT TIME]

AVAILABLE DEPARTMENTS:
Front desk, housekeeping, maintenance,
food and beverage, security and management.

OUTPUT:
1. Request category
2. Responsible department
3. Priority: critical, high, medium or low
4. Reason for priority
5. Recommended next action
6. Whether immediate human escalation is needed

CONSTRAINTS:
Flag potential safety or security issues for
immediate human escalation.
Do not claim the request has been completed.

## 2. Intended Workflow or Task

Guest request handling and departmental routing.

## 3. Problem Being Solved

Guest requests may be sent to the wrong department,
causing delays and inconsistent service.

## 4. Automation Potential

AI can assist with initial classification and
routing recommendations. Hotel staff must review
urgent requests and confirm the appropriate action.

## 5. Risks and Limitations

AI may incorrectly assess the urgency of a request.
Staff must retain responsibility for escalation
and operational decisions.