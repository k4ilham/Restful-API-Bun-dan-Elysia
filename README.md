powershell -c "irm bun.sh/install.ps1 | iex"

bun --version

bun create elysia bun-api

bun dev

bun add prisma@5.13.0 --save-dev

bunx prisma init

bunx prisma migrate dev --name posts

bun add @prisma/client@5.13.0