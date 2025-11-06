AfyaLink Backend — Local Developer Setup (Step-by-step)

1) Prereqs
- Node.js 18+, npm, Docker, Git

2) Clone & install
git clone <repo>
cd afyalink-backend
npm ci

3) Configure .env
DATABASE_URL=postgresql://postgres:postgres@localhost:5432/afyalink

4) Docker Compose
docker-compose up -d

5) Prisma
npx prisma generate
npx prisma migrate dev --name init

6) Seed data
npm run seed

7) Start dev server
npm run start:dev

8) Swagger docs at /api/docs
