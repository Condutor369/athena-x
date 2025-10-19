# athena-x
Plataforma de assistente
cd athena-x

# 2. Libs essenciais
pnpm add @supabase/supabase-js posthog-js zod lucide-react
pnpm add -D @types/node @types/react @types/react-dom

# 3. shadcn/ui (UI produtiva)
pnpm dlx shadcn-ui@latest init -d
pnpm dlx shadcn-ui@latest add button card input textarea dialog badge table alert
