# 🧠 **Tech Store** — Plataforma de Cursos Online  
📚 *Projeto Prático do Curso Descomplica (Advanced Front-End)*  

---

## 🚀 Visão Geral
**Tech Store** é um protótipo em fase inicial de uma plataforma moderna de **e-learning** desenvolvida com **Angular 17+**, projetada para oferecer uma experiência de aprendizado interativa e intuitiva para cursos técnicos.

---

## 🧩 Tecnologias Utilizadas
- ⚙️ **Angular 17+**
- 🎨 **Angular Material UI**
- 🧠 **NgRx** (gerenciamento de estado global)
- 🧰 **JSON Server** (mock da API)
- 🔁 **RxJS** (programação reativa)

---

## 💻 Funcionalidades Principais

### 🧑‍🎓 1. Área do Aluno
**Dashboard Personalizado**
- Lista de cursos matriculados  
- Indicadores de progresso  
- Última aula assistida  
- Total de aulas e aulas concluídas  

**Player de Curso**
- Menu lateral com currículo completo  
- Player de vídeo responsivo  
- Controles de navegação (anterior / próximo)  
- Marcação de aulas concluídas  
- Status de progresso por módulo  

---

### 🎓 2. Catálogo de Cursos
- Listagem em **grid** com cards informativos  
- Filtros por **nível** e **categoria**  
- Informações detalhadas:
  - Descrição  
  - Instrutor  
  - Carga horária  
  - Nível de dificuldade  
  - Preço  

---

### 🔐 3. Sistema de Autenticação
- Login seguro  
- Registro de novos usuários  
- Proteção de rotas via **Guards**  
- Persistência de sessão com **LocalStorage**  

---

### 🛒 4. Carrinho de Compras
- Adição e remoção de cursos  
- Atualização de quantidades  
- Cálculo automático do total  
- Checkout *(em desenvolvimento)*  

---

## 🔌 API Endpoints

### 📘 Cursos
| Método | Endpoint | Descrição |
|---------|-----------|------------|
| GET | `/api/courses` | Lista todos os cursos |
| GET | `/api/courses/:id` | Detalhes de um curso |

### 👤 Autenticação
| Método | Endpoint | Descrição |
|---------|-----------|------------|
| POST | `/api/auth/register` | Registro de usuário |
| POST | `/api/auth/login` | Login de usuário |

### 🎓 Área do Aluno
| Método | Endpoint | Descrição |
|---------|-----------|------------|
| GET | `/api/student/courses` | Cursos matriculados |
| GET | `/api/student/courses/:id/content` | Conteúdo do curso |
| POST | `/api/student/courses/:id/progress` | Atualiza progresso |
| POST | `/api/student/courses/:id/complete` | Marca aula como concluída |

---

## ⚙️ Instalação e Execução

### 📋 Pré-requisitos
- **Node.js** v18+
- **npm** v9+
- **Angular CLI** v17+

## 🎨 Recursos do Angular Material Implementados

- **MatToolbar** → Navegação superior  
- **MatSidenav** → Menu lateral  
- **MatCard** → Cards de cursos  
- **MatProgressBar** → Indicadores de progresso  
- **MatExpansionPanel** → Currículo do curso  
- **MatSnackBar** → Notificações  

---

## 🧱 Estado Global (NgRx)

Gerenciamento centralizado com Store para:
- Carrinho de compras  
- Autenticação  
- Estado do curso atual  

---

## 📱 Responsividade

- **Layout adaptativo** para:
  - 💻 **Desktop** (>1200px)
  - 📟 **Tablet** (768px–1199px)
  - 📱 **Mobile** (<768px)
- Grid system flexível  
- Media queries otimizadas  

---

## 🔒 Segurança

- Guards para rotas protegidas  
- Interceptor JWT para autenticação  
- Sanitização de URLs  
- Validação de formulários  

---

## ⚡ Performance

- Lazy Loading de módulos  
- Componentes Standalone  
- Otimização de imagens  
- Minificação de assets  

---

## 🧭 Próximas Implementações

- [ ] Sistema de busca avançada  
- [ ] Filtros de cursos  
- [ ] Checkout integrado  
- [ ] Área do instrutor  
- [ ] Sistema de avaliações  
- [ ] Download de materiais  
- [ ] Certificados automáticos  

🤝 Contribuição

## 🤝 Contribuição

- **Faça um fork do projeto**  
- **Crie uma branch para sua feature:**  
   git checkout -b feature/nova-funcionalidade  
- **Faça o commit das alterações:**  
   git commit -m "Adiciona nova funcionalidade"  
- **Envie a branch:**  
   git push origin feature/nova-funcionalidade  
- **Abra um Pull Request**
