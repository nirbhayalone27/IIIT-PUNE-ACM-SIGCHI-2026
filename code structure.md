project-runtime/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── ROADMAP.md
├── CODE_OF_CONDUCT.md
├── .gitignore
├── .env.example
├── docker-compose.yml
├── package.json
├── pnpm-workspace.yaml
├── turbo.json
│
├── apps/
│   │
│   ├── web/                      # Next.js Frontend
│   │
│   ├── api/                      # FastAPI Backend
│   │
│   └── docs/                     # Documentation website
│
├── packages/
│   │
│   ├── runtime/                  # ⭐ Core Runtime Engine
│   │
│   ├── ui/
│   │
│   ├── intent-engine/
│   │
│   ├── interface-generator/
│   │
│   ├── component-registry/
│   │
│   ├── ai-agents/
│   │
│   ├── explainability/
│   │
│   ├── accessibility/
│   │
│   ├── sdk/
│   │
│   ├── shared/
│   │
│   └── config/
│
├── infrastructure/
│   │
│   ├── docker/
│   │
│   ├── kubernetes/
│   │
│   ├── nginx/
│   │
│   └── monitoring/
│
├── scripts/
│
├── examples/
│
├── benchmarks/
│
├── tests/
│
├── assets/
│
└── .github/

#apps/web
web/

app/

components/

hooks/

providers/

lib/

services/

store/

styles/

types/

public/

#COMPONENTS
components/

layout/

sidebar/

header/

workspace/

runtime/

chat/

graph/

mindmap/

comparison/

timeline/

canvas/

knowledge/

animations/

accessibility/

shared/

ui/

#Runtime Components
runtime/

RuntimeProvider.tsx

RuntimeRenderer.tsx

RuntimeContext.tsx

RuntimeRegistry.ts

RuntimeLoader.ts

RuntimeSwitcher.ts

RuntimeAnimation.ts

#Interface Generator
interface-generator/

LearningGenerator.ts

ResearchGenerator.ts

DecisionGenerator.ts

PlanningGenerator.ts

CodingGenerator.ts

CanvasGenerator.ts

TimelineGenerator.ts

#Intent Engine
intent-engine/

IntentClassifier.ts

PromptAnalyzer.ts

IntentRouter.ts

IntentConfidence.ts

IntentSchema.ts

IntentMemory.ts

#AI Agents
agents/

ResearchAgent.ts

TeacherAgent.ts

PlannerAgent.ts

CriticAgent.ts

EngineerAgent.ts

ArchitectAgent.ts

FactChecker.ts

AccessibilityAgent.ts

#Explainability
explainability/

Confidence.ts

Evidence.ts

Sources.ts

Reasoning.ts

Hallucination.ts

Alternative.ts

#packages/runtime
runtime/

engine/

router/

state/

registry/

render/

animation/

workspace/

hooks/

types/

utils/

#Engine
engine/

RuntimeEngine.ts

RuntimeManager.ts

RuntimeLifecycle.ts

RuntimeEvents.ts

RuntimeStore.ts
