# NLW-IA
Este projeto envolve o desenvolvimento de duas ferramentas: o Upload AI, uma plataforma que simplifica o processo de upload de vídeos no YouTube e gera automaticamente títulos, descrições e materiais; e o Shorts Summary, uma aplicação web que transcreve e resume vídeos do YouTube.

**Front-end**: 
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [axios](https://axios-http.com/)
- [ffmpeg](https://ffmpeg.org/)
- [ai](https://www.npmjs.com/package/ai)

**Back-end**: 
- [Fastify](https://fastify.io/)
- [Prisma](https://www.prisma.io/)
- [OpenAI](https://openai.com/)
- [zod](https://github.com/colinhacks/zod)

<h2> 🔥 Iniciando o projeto: </h2>

Para executar a aplicação em sua máquina localmente, certifique-se de ter o Node.js e o npm instalados antes de prosseguir com as etapas abaixo:

1. Clone o repositorio:
   ```shell
   $ git clone https://github.com/your-username/upload.ai.git
   ```

2. Vá até a pasta:

   ```shell
   $ cd upload.ai-api
   ```

3. Instale as dependencias:

   ```shell
   $ npm install
   ```

4. Configure as variáveis de ambiente em um arquivo `.env`.

   ```shell
   # Examplo
   DATABASE_URL='file:./dev.db'
   OPENAI_API_KEY='sua-api-key-da-open-ai'
   ```

5. Inicie o banco de dados:

   ```shell
   # npx prisma migrate dev 
   ```

6. Popule a tabela de `prompts`:

   ```shell
   # npx prisma db seed
   ```

7. Inicie o servidor:

   ```shell
   $ pnpm run dev
   ```

Agora, com o projeto back-end em execução, execute o projeto front-end em um novo terminal seguido os seguintes passos:

1. Vá até a pasta:

   ```shell
   $ cd upload-ai && cd upload web
   ```

2. Instale as dependências:

   ```shell
   $ pnpm install
   
   ```

3. Inicie a aplicação:

   ```shell
   $ pnpm run dev
   ```

<h2>🎓 Certificado do Evento </h2>

<img style="height: 250px" src="https://raw.githubusercontent.com/gabrielarroyoc/nlw-ia/master/certificate.jpg"> </img>

