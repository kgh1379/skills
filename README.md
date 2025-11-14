Skills  기술
Skills are folders of instructions, scripts, and resources that Claude loads dynamically to improve performance on specialized tasks. Skills teach Claude how to complete specific tasks in a repeatable way, whether that's creating documents with your company's brand guidelines, analyzing data using your organization's specific workflows, or automating personal tasks.
스킬은 클로드가 전문 작업의 성과를 향상시키기 위해 동적으로 로드하는 지침, 스크립트 및 리소스 폴더입니다. 스킬은 클로드에게 회사 브랜드 가이드라인에 따른 문서 작성, 조직의 특정 워크플로를 사용한 데이터 분석, 개인 작업 자동화 등 특정 작업을 반복적으로 완료하는 방법을 알려줍니다.

For more information, check out:
자세한 내용은 다음을 확인하세요.

What are skills?  기술이란 무엇인가?
Using skills in Claude
클로드의 기술 사용
How to create custom skills
사용자 정의 기술을 만드는 방법
Equipping agents for the real world with Agent Skills
실제 세계의 에이전트에게 에이전트 기술 제공
About This Repository  이 저장소에 관하여
This repository contains example skills that demonstrate what's possible with Claude's skills system. These examples range from creative applications (art, music, design) to technical tasks (testing web apps, MCP server generation) to enterprise workflows (communications, branding, etc.).
이 저장소에는 클로드의 기술 시스템을 활용하여 무엇을 할 수 있는지 보여주는 예시 기술들이 포함되어 있습니다. 이러한 예시들은 창의적인 애플리케이션(미술, 음악, 디자인)부터 기술적인 작업(웹 앱 테스트, MCP 서버 생성), 엔터프라이즈 워크플로(커뮤니케이션, 브랜딩 등)까지 다양합니다.

Each skill is self-contained in its own directory with a SKILL.md file containing the instructions and metadata that Claude uses. Browse through these examples to get inspiration for your own skills or to understand different patterns and approaches.
각 기술은 Claude가 사용하는 지침과 메타데이터가 포함된 SKILL.md 파일을 통해 자체 디렉터리에 독립적으로 저장됩니다. 이 예시들을 살펴보고 자신의 기술에 대한 영감을 얻거나 다양한 패턴과 접근 방식을 이해해 보세요.

The example skills in this repo are open source (Apache 2.0). We've also included the document creation & editing skills that power Claude's document capabilities under the hood in the document-skills/ folder. These are source-available, not open source, but we wanted to share these with developers as a reference for more complex skills that are actively used in a production AI application.
이 저장소의 예시 스킬은 오픈 소스(Apache 2.0)입니다. 또한 Claude의 문서 기능을 구동하는 문서 생성 및 편집 스킬을 document-skills/ 폴더에 포함했습니다. 이 스킬들은 오픈 소스가 아닌 소스 코드로 제공되지만, 프로덕션 AI 애플리케이션에서 활발하게 사용되는 더 복잡한 스킬에 대한 참고 자료로 개발자들과 공유하고자 합니다.

Note: These are reference examples for inspiration and learning. They showcase general-purpose capabilities rather than organization-specific workflows or sensitive content.
참고: 이는 영감과 학습을 위한 참고 사례입니다. 조직별 워크플로나 민감한 콘텐츠가 아닌 일반적인 기능을 보여줍니다.

Disclaimer  부인 성명
These skills are provided for demonstration and educational purposes only. While some of these capabilities may be available in Claude, the implementations and behaviors you receive from Claude may differ from what is shown in these examples. These examples are meant to illustrate patterns and possibilities. Always test skills thoroughly in your own environment before relying on them for critical tasks.
이 기술은 데모 및 교육 목적으로만 제공됩니다. 이러한 기능 중 일부는 Claude에서 사용할 수 있지만, Claude에서 제공하는 구현 및 동작은 이 예제에서 보여지는 내용과 다를 수 있습니다. 이 예제는 패턴과 가능성을 보여주기 위한 것입니다. 중요한 작업에 사용하기 전에 항상 자신의 환경에서 기술을 철저히 테스트해 보세요.

Example Skills  예시 기술
This repository includes a diverse collection of example skills demonstrating different capabilities:
이 저장소에는 다양한 기능을 보여주는 다양한 예시 기술 컬렉션이 포함되어 있습니다.

Creative & Design  크리에이티브 & 디자인
algorithmic-art - Create generative art using p5.js with seeded randomness, flow fields, and particle systems
algorithmic-art - 시드된 무작위성, 흐름장 및 입자 시스템을 사용하여 p5.js를 사용하여 생성적 아트를 만듭니다.
canvas-design - Design beautiful visual art in .png and .pdf formats using design philosophies
canvas-design - 디자인 철학을 사용하여 .png 및 .pdf 형식으로 아름다운 시각 예술을 디자인하세요
slack-gif-creator - Create animated GIFs optimized for Slack's size constraints
slack-gif-creator - Slack의 크기 제한에 최적화된 애니메이션 GIF를 만듭니다.
Development & Technical  개발 및 기술
artifacts-builder - Build complex claude.ai HTML artifacts using React, Tailwind CSS, and shadcn/ui components
artifacts-builder - React, Tailwind CSS 및 shadcn/ui 구성 요소를 사용하여 복잡한 claude.ai HTML 아티팩트를 빌드합니다.
mcp-server - Guide for creating high-quality MCP servers to integrate external APIs and services
mcp-server - 외부 API 및 서비스를 통합하기 위한 고품질 MCP 서버를 만드는 가이드
webapp-testing - Test local web applications using Playwright for UI verification and debugging
webapp-testing - Playwright를 사용하여 UI 검증 및 디버깅을 위한 로컬 웹 애플리케이션 테스트
Enterprise & Communication
기업 및 커뮤니케이션
brand-guidelines - Apply Anthropic's official brand colors and typography to artifacts
브랜드 가이드라인 - Anthropic의 공식 브랜드 색상과 타이포그래피를 아티팩트에 적용
internal-comms - Write internal communications like status reports, newsletters, and FAQs
internal-comms - 상태 보고서, 뉴스레터, FAQ와 같은 내부 커뮤니케이션을 작성합니다.
theme-factory - Style artifacts with 10 pre-set professional themes or generate custom themes on-the-fly
theme-factory - 10개의 사전 설정된 전문 테마로 스타일 아티팩트를 만들거나 즉석에서 사용자 정의 테마를 생성하세요
Meta Skills  메타 스킬
skill-creator - Guide for creating effective skills that extend Claude's capabilities
skill-creator - 클로드의 역량을 확장하는 효과적인 스킬을 만드는 가이드
template-skill - A basic template to use as a starting point for new skills
template-skill - 새로운 기술을 시작하기 위한 시작점으로 사용할 수 있는 기본 템플릿
Document Skills  문서 기술
The document-skills/ subdirectory contains skills that Anthropic developed to help Claude create various document file formats. These skills demonstrate advanced patterns for working with complex file formats and binary data:
document-skills/ 하위 디렉터리에는 Anthropic이 Claude가 다양한 문서 파일 형식을 만드는 데 도움을 주기 위해 개발한 기술이 포함되어 있습니다. 이 기술은 복잡한 파일 형식과 이진 데이터 작업을 위한 고급 패턴을 보여줍니다.

docx - Create, edit, and analyze Word documents with support for tracked changes, comments, formatting preservation, and text extraction
docx - 추적된 변경 사항, 주석, 서식 유지 및 텍스트 추출을 지원하여 Word 문서를 만들고, 편집하고, 분석합니다.
pdf - Comprehensive PDF manipulation toolkit for extracting text and tables, creating new PDFs, merging/splitting documents, and handling forms
pdf - 텍스트 및 표 추출, 새 PDF 생성, 문서 병합/분할, 양식 처리를 위한 포괄적인 PDF 조작 툴킷
pptx - Create, edit, and analyze PowerPoint presentations with support for layouts, templates, charts, and automated slide generation
pptx - 레이아웃, 템플릿, 차트 및 자동 슬라이드 생성을 지원하여 PowerPoint 프레젠테이션을 만들고, 편집하고, 분석합니다.
xlsx - Create, edit, and analyze Excel spreadsheets with support for formulas, formatting, data analysis, and visualization
xlsx - 수식, 서식, 데이터 분석 및 시각화를 지원하는 Excel 스프레드시트를 만들고, 편집하고, 분석합니다.
Important Disclaimer: These document skills are point-in-time snapshots and are not actively maintained or updated. Versions of these skills ship pre-included with Claude. They are primarily intended as reference examples to illustrate how Anthropic approaches developing more complex skills that work with binary file formats and document structures.
중요 고지 사항: 이 문서 기술은 특정 시점의 스냅샷이며, 적극적으로 유지 관리되거나 업데이트되지 않습니다. 이러한 기술의 버전은 Claude에 사전 포함되어 제공됩니다. 이는 주로 Anthropic이 바이너리 파일 형식 및 문서 구조와 호환되는 더욱 복잡한 기술을 개발하는 방식을 보여주기 위한 참조 사례입니다.

Try in Claude Code, Claude.ai, and the API
Claude Code, Claude.ai 및 API에서 시도해 보세요.
Claude Code  클로드 코드
You can register this repository as a Claude Code Plugin marketplace by running the following command in Claude Code:
Claude Code에서 다음 명령을 실행하여 이 저장소를 Claude Code 플러그인 마켓플레이스로 등록할 수 있습니다.

/plugin marketplace add anthropics/skills
Then, to install a specific set of skills:
그런 다음 특정 기술 세트를 설치하려면 다음을 수행합니다.

Select Browse and install plugins
Browse and install plugins 선택하세요
Select anthropic-agent-skills
anthropic-agent-skills 선택
Select document-skills or example-skills
document-skills 또는 example-skills 선택하세요
Select Install now
Install now 선택하세요
Alternatively, directly install either Plugin via:
또는 다음을 통해 두 플러그인을 직접 설치하세요.

/plugin install document-skills@anthropic-agent-skills
/plugin install example-skills@anthropic-agent-skills
After installing the plugin, you can use the skill by just mentioning it. For instance, if you install the document-skills plugin from the marketplace, you can ask Claude Code to do something like: "Use the PDF skill to extract the form fields from path/to/some-file.pdf"
플러그인을 설치한 후에는 해당 스킬을 언급하는 것만으로도 사용할 수 있습니다. 예를 들어, 마켓플레이스에서 document-skills 플러그인을 설치하면 Claude Code에게 "PDF 스킬을 사용하여 path/to/some-file.pdf에서 양식 필드를 추출합니다"와 같은 작업을 요청하면 됩니다.

Claude.ai  클로드.ai
These example skills are all already available to paid plans in Claude.ai.
이러한 예시 기술은 모두 Claude.ai의 유료 플랜에서 이미 사용할 수 있습니다.

To use any skill from this repository or upload custom skills, follow the instructions in Using skills in Claude.
이 저장소의 스킬을 사용하거나 사용자 지정 스킬을 업로드하려면 Claude에서 스킬 사용 의 지침을 따르세요.

Claude API  클로드 API
You can use Anthropic's pre-built skills, and upload custom skills, via the Claude API. See the Skills API Quickstart for more.
Anthropic의 기본 스킬을 사용하고, Claude API를 통해 사용자 지정 스킬을 업로드할 수 있습니다. 자세한 내용은 Skills API 빠른 시작을 참조하세요.

Creating a Basic Skill  기본 기술 만들기
Skills are simple to create - just a folder with a SKILL.md file containing YAML frontmatter and instructions. You can use the template-skill in this repository as a starting point:
스킬은 간단하게 만들 수 있습니다. YAML 프론트매터와 지침이 포함된 SKILL.md 파일이 있는 폴더만 있으면 됩니다. 이 저장소의 템플릿 스킬을 시작점으로 사용할 수 있습니다.

---
name: my-skill-name
description: A clear description of what this skill does and when to use it
---

# My Skill Name

[Add your instructions here that Claude will follow when this skill is active]

## Examples
- Example usage 1
- Example usage 2

## Guidelines
- Guideline 1
- Guideline 2
The frontmatter requires only two fields:
서문에는 두 개의 필드만 필요합니다.

name - A unique identifier for your skill (lowercase, hyphens for spaces)
name - 기술에 대한 고유 식별자(소문자, 공백은 하이픈)
description - A complete description of what the skill does and when to use it
description - 해당 스킬의 기능과 사용 시기를 완벽하게 설명합니다.
The markdown content below contains the instructions, examples, and guidelines that Claude will follow. For more details, see How to create custom skills.
아래 마크다운 콘텐츠에는 클로드가 따라야 할 지침, 예시, 가이드라인이 포함되어 있습니다. 자세한 내용은 사용자 지정 스킬을 만드는 방법을 참조하세요.

Partner Skills  파트너 기술
Skills are a great way to teach Claude how to get better at using specific pieces of software. As we see awesome example skills from partners, we may highlight some of them here:
기술은 클로드에게 특정 소프트웨어 사용법을 더 잘 가르치는 좋은 방법입니다. 파트너들의 훌륭한 기술 예시를 살펴보았는데, 그중 몇 가지를 여기에서 강조해 보겠습니다.

Notion - Notion Skills for Claude
Notion - Claude를 위한 Notion 기술
