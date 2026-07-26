# Reference
## Agent
<details><summary><code>client.agent.<a href="/src/api/resources/agent/client/Client.ts">getConversation</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agent.getConversation();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.GetConversationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agent.<a href="/src/api/resources/agent/client/Client.ts">createMessage</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agent.createMessage({
    content: "content"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.CreateAgentMessageRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Goals
<details><summary><code>client.goals.<a href="/src/api/resources/goals/client/Client.ts">listGoals</a>() -> Darwin.ListGoalsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.goals.listGoals();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `GoalsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.goals.<a href="/src/api/resources/goals/client/Client.ts">createGoal</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.goals.createGoal({
    intent: "intent"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.CreateGoalRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GoalsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.goals.<a href="/src/api/resources/goals/client/Client.ts">getGoal</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.goals.getGoal({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.GetGoalRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GoalsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Approvals
<details><summary><code>client.approvals.<a href="/src/api/resources/approvals/client/Client.ts">listApprovals</a>({ ...params }) -> Darwin.ListApprovalsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.approvals.listApprovals();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.ListApprovalsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ApprovalsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.approvals.<a href="/src/api/resources/approvals/client/Client.ts">decideApproval</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.approvals.decideApproval({
    id: "id",
    decision: "APPROVE"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Darwin.ApprovalDecisionRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ApprovalsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Integrations
<details><summary><code>client.integrations.<a href="/src/api/resources/integrations/client/Client.ts">getIntegrations</a>() -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.integrations.getIntegrations();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IntegrationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

