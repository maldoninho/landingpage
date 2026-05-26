[upsell.html](https://github.com/user-attachments/files/28247816/upsell.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oferta Especial — Mestre do Estoque 360</title>
  <meta name="description" content="Aproveite esta oferta exclusiva complementar ao Mestre do Estoque 360" />
  <meta name="robots" content="noindex, nofollow" />
  <meta property="og:title" content="Oferta Especial — Mestre do Estoque 360" />
  <meta property="og:description" content="Oferta exclusiva para novos clientes." />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet" />
  <style>
    *,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
    :root{
      --bg:#09090b;--surface:#18181b;--border:rgba(255,255,255,0.06);
      --border-hover:rgba(255,255,255,0.12);--text:#fafafa;
      --text-muted:rgba(255,255,255,0.5);--text-dim:rgba(255,255,255,0.25);
      --accent:#00c853;--accent-dim:rgba(0,200,83,0.1);--accent-glow:rgba(0,200,83,0.25);
      --blue:#2979ff;--gold:#d4a853;--red:#ff4444;
      --radius:16px;--radius-sm:10px;--transition:0.35s cubic-bezier(0.22,1,0.36,1)
    }
    html{scroll-behavior:smooth;-webkit-font-smoothing:antialiased}
    body{
      font-family:'Inter',-apple-system,BlinkMacSystemFont,sans-serif;
      background:var(--bg);color:var(--text);line-height:1.6;overflow-x:hidden
    }
    .container{max-width:780px;margin:0 auto;padding:0 20px}
    section{padding:60px 0;text-align:center}

    nav{padding:16px 0;border-bottom:1px solid var(--border)}
    nav .container{display:flex;align-items:center;justify-content:space-between}
    .logo{font-size:1rem;font-weight:800;letter-spacing:-.02em}
    .logo em{font-style:normal;color:var(--accent)}

    .tag{
      display:inline-flex;align-items:center;gap:6px;
      font-size:.7rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;
      color:var(--gold);background:rgba(212,168,83,.1);
      border:1px solid rgba(212,168,83,.12);padding:5px 14px;border-radius:100px;margin-bottom:20px
    }
    h1{font-size:clamp(1.6rem,3vw,2.4rem);font-weight:800;line-height:1.12;letter-spacing:-.025em;margin-bottom:12px}
    h1 .gt{background:linear-gradient(135deg,var(--accent),var(--blue));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
    .sub-text{font-size:.95rem;color:var(--text-muted);max-width:500px;margin:0 auto 32px;line-height:1.7}

    .transition-bar{
      display:flex;align-items:center;justify-content:center;gap:16px;
      padding:14px;margin-bottom:32px;font-size:.82rem;color:var(--text-dim);
      background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-sm)
    }
    .transition-bar strong{color:var(--accent)}

    .upsell-card{
      max-width:600px;margin:0 auto;
      background:linear-gradient(135deg,rgba(212,168,83,.06),rgba(0,200,83,.04));
      border:1px solid rgba(212,168,83,.15);border-radius:var(--radius);
      padding:44px 36px;position:relative;overflow:hidden
    }
    .upsell-card::before{
      content:'';position:absolute;top:-60%;left:-60%;width:220%;height:220%;
      background:conic-gradient(from 0deg at 50% 50%,transparent 0%,rgba(212,168,83,.04) 25%,transparent 50%);
      animation:spin 12s linear infinite
    }
    @keyframes spin{to{transform:rotate(360deg)}}
    .upsell-card>*{position:relative;z-index:2}
    .upsell-label{font-size:.75rem;font-weight:700;color:var(--gold);letter-spacing:.12em;text-transform:uppercase;margin-bottom:8px}
    .upsell-title{font-size:1.3rem;font-weight:700;margin-bottom:8px}
    .upsell-price{font-size:2.8rem;font-weight:900;line-height:1;margin:12px 0}
    .upsell-price s{font-size:.8rem;font-weight:400;color:var(--text-dim)}
    .upsell-install{font-size:.85rem;color:var(--text-dim);margin-bottom:24px}
    .upsell-bullets{text-align:left;display:inline-block;margin-bottom:28px}
    .upsell-bullets li{display:flex;align-items:center;gap:8px;padding:5px 0;font-size:.85rem;color:var(--text-muted);list-style:none}
    .upsell-bullets li::before{content:'✓';color:var(--gold);font-weight:700}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;gap:10px;
      padding:16px 44px;border-radius:60px;font-weight:700;font-size:1rem;
      text-decoration:none;cursor:pointer;border:none;
      transition:all var(--transition);font-family:inherit;width:100%
    }
    .btn-primary{
      background:linear-gradient(135deg,var(--gold),#b8913a);color:#000;
      box-shadow:0 6px 28px rgba(212,168,83,.25)
    }
    .btn-primary:hover{transform:translateY(-2px);box-shadow:0 10px 40px rgba(212,168,83,.4)}
    .btn-skip{
      display:inline-block;margin-top:20px;font-size:.82rem;color:var(--text-dim);
      text-decoration:underline;cursor:pointer;transition:color var(--transition)
    }
    .btn-skip:hover{color:var(--text-muted)}

    .comparison{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:32px;max-width:600px;margin-left:auto;margin-right:auto}
    .comp-box{padding:24px 20px;border-radius:var(--radius-sm);text-align:left}
    .comp-box.basic{background:var(--surface);border:1px solid var(--border)}
    .comp-box.premium{background:rgba(212,168,83,.04);border:1px solid rgba(212,168,83,.15)}
    .comp-box h4{font-size:.9rem;font-weight:700;margin-bottom:12px;display:flex;align-items:center;gap:6px}
    .comp-box li{display:flex;align-items:flex-start;gap:6px;padding:4px 0;font-size:.78rem;color:var(--text-muted);list-style:none}
    .comp-box .yes{color:var(--accent)}.comp-box .no{color:var(--red);opacity:.5}
    @media(max-width:500px){.comparison{grid-template-columns:1fr}}

    .guarantee-inline{
      display:flex;align-items:center;justify-content:center;gap:10px;
      margin-top:20px;padding:14px;border-radius:var(--radius-sm);
      background:rgba(255,255,255,.02);font-size:.82rem;color:var(--text-dim)
    }
    .guarantee-inline strong{color:var(--text)}

    .trust-bar{display:flex;justify-content:center;gap:24px;margin-top:20px;flex-wrap:wrap}
    .trust-item{display:flex;align-items:center;gap:6px;font-size:.75rem;color:var(--text-dim)}

    footer{text-align:center;padding:32px 0;font-size:.75rem;color:var(--text-dim);border-top:1px solid var(--border);margin-top:40px}

    @media(max-width:480px){
      .upsell-card{padding:32px 20px}
      .btn{font-size:.9rem;padding:14px 24px}
    }
  </style>
</head>
<body>

  <nav>
    <div class="container">
      <div class="logo">Mestre do <em>Estoque 360</em></div>
      <div style="font-size:.75rem;color:var(--text-dim)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
        Ambiente seguro
      </div>
    </div>
  </nav>

  <section>
    <div class="container">
      <div class="transition-bar">
        ✅ <span>Seu acesso ao <strong>Mestre do Estoque 360</strong> foi enviado para o seu e-mail!</span>
      </div>

      <span class="tag">Oferta Exclusiva</span>
      <h1>Não Perca Esta <span class="gt">Oportunidade Única</span></h1>
      <p class="sub-text">Seus clientes estão prontos para pagar. Resta saber se você está pronto para atendê-los.</p>

      <div class="upsell-card">
        <div class="upsell-label">Oferta especial — só hoje</div>
        <div class="upsell-title">Kit Gestão de Estoque Completo</div>
        <div class="upsell-price"><s>R$ 197</s> R$ 47</div>
        <div class="upsell-install">ou 12x de R$ 4,67</div>
        <ul class="upsell-bullets">
          <li>Planilha de Curva ABC Premium (editável)</li>
          <li>Checklist de Inventário Cíclico Diário</li>
          <li>Template de Relatório de Acuracidade</li>
          <li>Planilha de Giro de Estoque automática</li>
          <li>Guia Rápido de Precificação por Margem</li>
          <li>Planilha de Desova Inteligente</li>
        </ul>
        <button class="btn btn-primary" onclick="handleUpsell()">
          Sim, Quero Aproveitar!
        </button>
        <a href="#" class="btn-skip" onclick="handleSkip()">Não, obrigado. Prefiro ficar apenas com o ebook.</a>
      </div>

      <div class="guarantee-inline">
        <span style="font-size:1.2rem">🛡️</span>
        <span><strong>Garantia de 7 dias</strong> — Risco zero. Se não gostar, devolvemos seu dinheiro.</span>
      </div>

      <div class="trust-bar" style="margin-top:16px">
        <span class="trust-item">🔒 Pagamento 100% seguro</span>
        <span class="trust-item">📥 Acesso imediato</span>
        <span class="trust-item">🛡️ Garantia de 7 dias</span>
      </div>

      <div class="comparison">
        <div class="comp-box basic">
          <h4>📘 Plano Básico</h4>
          <ul>
            <li><span class="yes">✓</span> Ebook Mestre do Estoque 360</li>
            <li><span class="yes">✓</span> Bônus: Operação Estoque Vivo</li>
            <li><span class="no">✕</span> Planilhas profissionais</li>
            <li><span class="no">✕</span> Templates editáveis</li>
            <li><span class="no">✕</span> Guia de precificação</li>
          </ul>
        </div>
        <div class="comp-box premium">
          <h4>⭐ Plano Completo</h4>
          <ul>
            <li><span class="yes">✓</span> Tudo do plano básico</li>
            <li><span class="yes">✓</span> Planilha Curva ABC Premium</li>
            <li><span class="yes">✓</span> Checklist Inventário Cíclico</li>
            <li><span class="yes">✓</span> Template Relatório Acuracidade</li>
            <li><span class="yes">✓</span> Planilha Giro + Desova</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>© 2026 Mestre do Estoque 360 — Todos os direitos reservados.</p>
      <p style="margin-top:6px">Produto digital. Preços e condições sujeitos a alteração sem aviso prévio.</p>
    </div>
  </footer>

  <script>
    function handleUpsell() {
      alert('🎉 Oferta adicionada ao seu pedido!');
      window.location.href = 'index.html';
    }
    function handleSkip(e) {
      e.preventDefault();
      window.location.href = 'index.html';
    }
  </script>
</body>
</html>
