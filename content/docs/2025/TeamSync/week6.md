# Week 6

## Links

- **Deployment**: team-sync.online
- **API Docs**
    
    team-sync.online/projects/api/v1/swagger-ui/index.html
    
    team-sync.online/resume/api/v1/swagger-ui/index.html
    
    team-sync.online/auth/api/v1/swagger-ui/index.html
    
- **Design**: [https://www.figma.com/design/H76U45VUArQSuD5ev0anDV/TeamSync-Design?node-id=0-1&t=Tv75bgJoMgN6eCPm-1](https://www.figma.com/design/H76U45VUArQSuD5ev0anDV/TeamSync-Design?node-id=0-1&t=Tv75bgJoMgN6eCPm-1)

## Final deliverables

### **Current implementation**

**Problem**

> Students struggle with inefficient, time-consuming team formation for Capstone/elective projects, leading to unbalanced teams and delayed project starts. Manual searches via Telegram groups cause outdated information, unclear progress, and social barriers to outreach.
> 

**Solution**

> A centralized platform that streamlines team formation through AI-driven matchmaking, transparent project discovery, and structured applications.
> 

### **Key features implemented**

1. **Project hub**
    - Create/view projects with descriptions, required skills, and open roles
    - Real-time visibility into team composition
2. **Profiles**
    - Students highlight their skills and interests
3. **AI Matchmaking**
    - Recommends projects to students based on skill compatibility
4. **Application system**
    - 1-click applications for open roles
    - Accept/reject workflow
5. **Team Dashboard**
    - Track accepted members
6. **Search & Filters**
    - Find projects by skills, roles or course

## **Future expansion plans**

### **Product vision**

Scale TeamSync into a cross-ecosystem platform for universities, hackathons, and corporate projects within 3–5 years.

### **Strategic Priorities**

1. **Teammate Matching** 
    
    **User Profiles**
    
    - Skills/experience showcase + availability calendars
    
    **AI Teammate Recommendations**
    
    - "Find Teammates" tab suggesting compatible peers
    
    **Direct Collaboration Tools**
    
    - Icebreaker chats for pre-team formation
2. **Ecosystem Integration**
    - **Universities**
        
        Sync with LMS to auto-import courses/skills
        
    - **Hackathons**
        
        Partner with platforms for event team formation
        
3. **Enhanced AI Capabilities**
    - **Predictive team balancing**
    - **Bias reduction**
        
        Anonymous applications to prioritize skills over demographics
        
4. **Monetization**
    - **B2B Licensing**:
        - Universities: Paid access for Capstone/elective course management
        - Hackathons: Tiered pricing for analytics
    - **Premium Features**:
        - Resume builder with verified project experience
        - Advanced analytics for instructor
5. **User Experience Evolution**
    - **Research hub** – ****publish/find academic research opportunities

### Tech stack

|  | **Choice** | **Justification** |
| --- | --- | --- |
| **Frontend** | React | For building dynamic and high-performance user interfaces and server-side rendering capabilities. |
|  | TypeScript | A strongly typed programming language that builds on JavaScript, providing better tooling at any scale. |
|  | Tailwind CSS | A utility-first CSS framework for rapid UI development with consistent and responsive design. |
| **Backend** | Java/Spring Boot | Robust REST APIs, team expertise |
| **Database** | PostgreSQL | ACID compliance for user/project data |
|  | KeyDB | Fast session/matching-cache access |
| **ML** | Python | For its simplicity and extensive libraries for data processing and machine learning. |
| **Infra** | Docker + Docker Compose | Environment consistency, TA reproducibility |
|  | GitHub Actions (CI/CD) | Automated testing/deployment |

## Presentation draft

[LINK](https://miro.com/app/board/uXjVJdA5G0Q=/?share_link_id=352339515758)

# Plan for live demo

| 1st browser | 2nd browser (or incognito mode) |
| --- | --- |
| Registration | - |
| Project creation | - |
| - | Filter projects |
| - | Find created project |
|  | Apply to it |
| See application |  |
| Accept/reject |  |
| - | Change skills/project positions |
| - | Reload page, see that recommendations are changes |

# Weekly commitments

## ML

This week

## Backend

This week

## Frontend

This week

## Design

This week landing page

## DevOps

This week

## Individual contribution of each participant

| Team member | Contribution | Jira tasks |
| --- | --- | --- |
| Diana MInnakhmetova (Lead) | wrote report, held 2 meetings, made draft for presentation slides, made plan for live demo, fixed design issues, [made product strategy for future work](https://miro.com/app/board/uXjVIk_JdUg=/?share_link_id=897980657893), [made landing page](https://www.figma.com/design/H76U45VUArQSuD5ev0anDV/TeamSync-Design?node-id=0-1&t=q9Js5bd4HpF30mWq-1) | TS-226. TS-227, TS-237 |
| Danis Sharafiev |  |  |
| Daria Alexandrova |  |  |
| Stepan Dementev |  |  |
| Elizaveta Zagurskih |  |  |
| Kamilya Shakirova |  |  |

## Confirmation of the code’s operability

We confirm that the code in the main branch:

- [ ]  In working condition.
- [ ]  Run via docker-compose (or another alternative described in the `README.md`).