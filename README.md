# projeto"use client";

export default function PrivacyPolicyPage() {
  return (
    <div
      style={{
        minHeight: "100vh",
        backgroundColor: "#f9fafb",
        paddingTop: "40px",
        paddingBottom: "40px",
      }}
    >
      <div
        style={{
          maxWidth: "800px",
          margin: "0 auto",
          paddingLeft: "20px",
          paddingRight: "20px",
        }}
      >
        {/* Header */}
        <div style={{ marginBottom: "40px" }}>
          <h1
            style={{
              fontSize: "32px",
              fontWeight: "bold",
              color: "#1F2937",
              marginBottom: "8px",
            }}
          >
            Política de Privacidade
          </h1>
          <p style={{ fontSize: "14px", color: "#6B7280" }}>
            Última atualização: {new Date().toLocaleDateString("pt-BR")}
          </p>
        </div>

        {/* Content */}
        <div
          style={{
            backgroundColor: "#fff",
            borderRadius: "12px",
            padding: "32px",
            boxShadow: "0 1px 3px rgba(0,0,0,0.1)",
          }}
        >
          {/* Introduction */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              1. Introdução
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Bem-vindo à Calculadora Elétrica. Nós nos comprometemos em
              proteger sua privacidade e garantir que você tenha uma experiência
              positiva em nosso aplicativo. Esta Política de Privacidade explica
              como coletamos, usamos e protegemos suas informações.
            </p>
          </section>

          {/* Data Collection */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              2. Coleta de Dados
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Nossa aplicação coleta e armazena o seguinte:
            </p>
            <ul
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.8",
                marginLeft: "20px",
                marginBottom: "12px",
              }}
            >
              <li style={{ marginBottom: "8px" }}>
                <strong>Histórico de Cálculos:</strong> Registramos os cálculos
                que você realiza (potência, energia e resistência) para sua
                conveniência e referência futura.
              </li>
              <li style={{ marginBottom: "8px" }}>
                <strong>Dados Locais:</strong> Todos os dados são armazenados
                localmente no seu dispositivo. Não coletamos dados de
                localização, contatos ou outras informações pessoais.
              </li>
            </ul>
          </section>

          {/* Data Usage */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              3. Como Usamos Seus Dados
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Os dados coletados são usados exclusivamente para:
            </p>
            <ul
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.8",
                marginLeft: "20px",
                marginBottom: "12px",
              }}
            >
              <li style={{ marginBottom: "8px" }}>
                Manter um histórico de seus cálculos para sua conveniência
              </li>
              <li style={{ marginBottom: "8px" }}>
                Melhorar a experiência do usuário no aplicativo
              </li>
              <li style={{ marginBottom: "8px" }}>
                Permitir que você revise cálculos anteriores
              </li>
            </ul>
          </section>

          {/* Data Storage */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              4. Armazenamento de Dados
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              <strong>Armazenamento Local:</strong> Todos os dados são
              armazenados localmente no seu dispositivo usando o armazenamento
              nativo do aplicativo. Nenhum dado é enviado para servidores
              externos ou compartilhado com terceiros.
            </p>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              <strong>Controle do Usuário:</strong> Você pode limpar seu
              histórico de cálculos a qualquer momento através da seção de
              Configurações do aplicativo.
            </p>
          </section>

          {/* Data Sharing */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              5. Compartilhamento de Dados
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Nós <strong>não compartilhamos</strong> seus dados com terceiros.
              Seus cálculos e histórico permanecem privados e são armazenados
              apenas no seu dispositivo.
            </p>
          </section>

          {/* Security */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              6. Segurança
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Como todos os dados são armazenados localmente no seu dispositivo,
              a segurança depende das medidas de segurança do seu dispositivo.
              Recomendamos manter seu dispositivo atualizado e protegido com uma
              senha ou biometria.
            </p>
          </section>

          {/* User Rights */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              7. Seus Direitos
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Você tem o direito de:
            </p>
            <ul
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.8",
                marginLeft: "20px",
                marginBottom: "12px",
              }}
            >
              <li style={{ marginBottom: "8px" }}>
                Acessar seus dados a qualquer momento
              </li>
              <li style={{ marginBottom: "8px" }}>
                Deletar seu histórico de cálculos
              </li>
              <li style={{ marginBottom: "8px" }}>
                Desinstalar o aplicativo para remover todos os dados
              </li>
            </ul>
          </section>

          {/* Changes to Policy */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              8. Alterações nesta Política
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Podemos atualizar esta Política de Privacidade de tempos em
              tempos. Notificaremos você sobre qualquer mudança significativa
              publicando a nova política no aplicativo.
            </p>
          </section>

          {/* Contact */}
          <section style={{ marginBottom: "32px" }}>
            <h2
              style={{
                fontSize: "20px",
                fontWeight: "600",
                color: "#1F2937",
                marginBottom: "12px",
              }}
            >
              9. Contato
            </h2>
            <p
              style={{
                fontSize: "14px",
                color: "#4B5563",
                lineHeight: "1.6",
                marginBottom: "12px",
              }}
            >
              Se você tiver dúvidas sobre esta Política de Privacidade ou sobre
              como tratamos seus dados, entre em contato conosco através do site{" "}
              <a
                href="https://createanything.com"
                style={{
                  color: "#1E40AF",
                  textDecoration: "none",
                  fontWeight: "500",
                }}
              >
                createanything.com
              </a>
              .
            </p>
          </section>

          {/* Compliance */}
          <section
            style={{
              backgroundColor: "#EFF6FF",
              borderLeft: "4px solid #1E40AF",
              padding: "16px",
              borderRadius: "8px",
            }}
          >
            <h2
              style={{
                fontSize: "16px",
                fontWeight: "600",
                color: "#1E40AF",
                marginBottom: "8px",
              }}
            >
              ✓ Conformidade com Diretrizes
            </h2>
            <p
              style={{ fontSize: "12px", color: "#1E40AF", lineHeight: "1.6" }}
            >
              Esta política está em conformidade com as diretrizes da App Store
              (5.1.1 - Data Collection and Privacy) e LGPD (Lei Geral de
              Proteção de Dados).
            </p>
          </section>
        </div>
      </div>
    </div>
  );
}



