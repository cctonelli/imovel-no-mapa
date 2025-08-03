# Imóvel no Mapa

## 🏠 Sobre o Projeto

Sistema de mapeamento de imóveis com React, Supabase e Leaflet. Plataforma para visualização e cadastro de propriedades em mapa interativo.

## 🚀 Tecnologias Utilizadas

- **Frontend**: React 18, TypeScript, Vite
- **UI Components**: Radix UI, shadcn/ui, Tailwind CSS
- **Mapas**: Leaflet, React Leaflet
- **Backend**: Supabase (PostgreSQL, Auth, Storage)
- **Estado**: TanStack Query (React Query)
- **Formulários**: React Hook Form + Zod
- **Roteamento**: React Router DOM

## 📋 Funcionalidades

### ✅ Implementadas
- 🗺️ Mapa interativo com Leaflet
- 🏠 Visualização de propriedades no mapa
- 📝 Formulário de cadastro de imóveis
- 🔐 Sistema de autenticação (Supabase Auth)
- 👤 Gerenciamento de usuários e perfis
- 🏢 Sistema de imobiliárias
- 📊 Dashboard básico
- 🔒 Row Level Security (RLS)
- 📱 Design responsivo

### 🚧 Em Desenvolvimento
- 🔍 Filtros avançados de busca
- 📸 Upload de imagens
- 💰 Sistema de pagamentos
- 📧 Notificações por email
- 📈 Analytics e relatórios

## 🛠️ Instalação e Configuração

### Pré-requisitos
- Node.js 18+ 
- npm ou yarn
- Conta no Supabase

### Passos para Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/cctonelli/imovel-no-mapa.git
cd imovel-no-mapa
```

2. **Instale as dependências**
```bash
npm install --legacy-peer-deps
```

3. **Configure as variáveis de ambiente**
```bash
cp .env.example .env
```

Edite o arquivo `.env` com suas configurações:
```env
VITE_SUPABASE_URL=https://dpriqlfwqlkxuthhjlav.supabase.co
VITE_SUPABASE_ANON_KEY=sua_chave_anonima_aqui
```

4. **Execute o projeto**
```bash
npm run dev
```

O projeto estará disponível em `http://localhost:8080`

## 🗄️ Banco de Dados

### Estrutura Principal
- **users**: Usuários do sistema
- **user_roles**: Papéis dos usuários (admin, imobiliaria, cliente)
- **imobiliarias**: Empresas imobiliárias
- **imoveis**: Propriedades/imóveis
- **categorias_imoveis**: Categorias de imóveis
- **planos**: Planos de assinatura
- **pagamentos**: Histórico de pagamentos
- **notificacoes**: Sistema de notificações

### Conexão Direta PostgreSQL
```
postgresql://postgres:[BOX05@#$]@db.dpriqlfwqlkxuthhjlav.supabase.co:5432/postgres
```

## 🔧 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Build para produção
- `npm run build:dev` - Build para desenvolvimento
- `npm run lint` - Executa o linter
- `npm run preview` - Preview do build

## 🚀 Deploy

### Vercel (Recomendado)
1. Conecte seu repositório GitHub ao Vercel
2. Configure as variáveis de ambiente
3. Deploy automático a cada push

### Netlify
1. Conecte seu repositório ao Netlify
2. Configure as variáveis de ambiente
3. Build command: `npm run build`
4. Publish directory: `dist`

## 🔐 Segurança

- ✅ Row Level Security (RLS) habilitado
- ✅ Autenticação via Supabase Auth
- ✅ Validação de formulários com Zod
- ✅ Sanitização de dados
- ✅ HTTPS obrigatório em produção

## 📚 Documentação Adicional

- [INTEGRATION_GUIDE.md](./INTEGRATION_GUIDE.md) - Guia de integração completo
- [DATABASE_CONNECTION.md](./DATABASE_CONNECTION.md) - Configurações de banco
- [PROJECT_SUMMARY.md](./PROJECT_SUMMARY.md) - Resumo técnico do projeto

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🔗 Links Úteis

- **Lovable Project**: https://lovable.dev/projects/f52c3c56-0ced-4f9f-83c7-8253f72a487e
- **Supabase Dashboard**: https://supabase.com/dashboard/project/dpriqlfwqlkxuthhjlav
- **GitHub Repository**: https://github.com/cctonelli/imovel-no-mapa

---

**Desenvolvido com ❤️ usando React, Supabase e Leaflet**