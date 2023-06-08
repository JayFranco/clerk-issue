1. Commit to Git
2. Create DB on PlanetScale
3. Add DATABASE_URL to .env file + add generator & datasource in schema.prisma
4. Run "npx prisma db push" to tell Prisma set the DB based on the Schema
5. Run "npx prisma studio" to verify that there are no error
6. Commit to Git
7. Deploy to Vercel (don't forget to add DATABASE_URL env var)
8. Add Clerks env var to .env file and in Vercel




Quick tricks:
- git add -p