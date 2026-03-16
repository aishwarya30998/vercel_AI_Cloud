1. instant folder - Deploying a simple FastAPI and LLM app on vercel
2. Saas folder - Buiulding a simple fullstack(frontend and backend application)
- A Business Idea Generator - an AI-powered SaaS application that:
- Has a modern React frontend built with Next.js (using Pages Router for stability)
- Uses TypeScript for type safety
-Connects to a FastAPI backend
- Streams AI responses in real-time
- Renders beautiful Markdown content
- Use clerk for user authentication and login
- Add supscription tiers and billing with Clerk payment gateway or stripe for payment processing
- Deploys seamlessly to production in vercel
----- In the same SaaS folder replaces the Bussiness idea generator code with healthcare application usecase
- A healthcare application that:
- Takes doctor's consultation notes as input
- Generates professional summaries for medical records
- Creates actionable next steps for the doctor
- Drafts patient-friendly email communications
- Uses structured forms with date pickers
- Streams AI-generated content in real-time

Hurray!!!! - Healthcare Consultation Assistant Delopyed on Vercel 
Try it yourself   - https://saas-970tzh7qj-aishwaryas-projects-e5dddcfa.vercel.app/

3. Saas_AWS  folder
---- Move Healthcare Consultation Assistant from Vercel and deploy it to AWS using Docker containers and App Runner.
Used ECR to push docker container to it and store the container repository
used IAM policies and users to assign roles
Used AWS APP Runner to delopy and host the applicaion
used cloudwatch logs to monitor



























Inspired from ----- https://github.com/ed-donner/production
