# First Workflow: NASA Solar Flare Report

**Purpose:**  
This workflow fetches solar flare data from NASA's DONKI API every Monday and sends reports to Postbin. It helps track solar activity automatically.

---

## **Workflow Steps**
1. **Schedule Trigger**
   - Runs every Monday at 9:00 AM.
2. **NASA Node**
   - Fetches solar flare data from the last 7 days.
   - Uses API key credentials from NASA.
3. **If Node**
   - Splits the data into high-class (X) and lower-class (A–M) solar flares.
4. **Postbin Nodes**
   - Sends reports for each branch to a Postbin bin for testing.

---

## **Key Concepts Learned**
- Trigger nodes to start workflows automatically.
- Setting up and using credentials in n8n.
- Using expressions to manipulate data.
- Conditional logic with the If node.
- Testing workflows and inspecting output.


