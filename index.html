<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teste: Você Está Travado? | Destravando Você</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .container {
            max-width: 700px;
            width: 100%;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px 30px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 900;
        }

        .header p {
            font-size: 1.2em;
            opacity: 0.95;
        }

        .content {
            padding: 40px 30px;
        }

        .intro-section {
            text-align: center;
            margin-bottom: 40px;
        }

        .intro-section h2 {
            color: #333;
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .intro-section p {
            color: #666;
            font-size: 1.1em;
            line-height: 1.6;
        }

        .quiz-section {
            display: none;
        }

        .quiz-section.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .question {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            border-left: 5px solid #667eea;
        }

        .question h3 {
            color: #333;
            font-size: 1.2em;
            margin-bottom: 15px;
        }

        .options {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .option {
            background: white;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            padding: 15px 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .option:hover {
            border-color: #667eea;
            background: #f0f4ff;
            transform: translateX(5px);
        }

        .option input[type="radio"] {
            width: 20px;
            height: 20px;
            cursor: pointer;
        }

        .option label {
            cursor: pointer;
            flex: 1;
            font-size: 1em;
            color: #333;
        }

        .btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 18px 40px;
            font-size: 1.2em;
            font-weight: 600;
            border-radius: 50px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
            transition: transform 0.3s ease;
        }

        .btn:hover {
            transform: scale(1.05);
        }

        .btn-secondary {
            background: white;
            color: #667eea;
            border: 2px solid #667eea;
        }

        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }

        .resultado-section {
            display: none;
            text-align: center;
        }

        .resultado-section.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        .score-circle {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 30px auto;
            font-size: 3em;
            font-weight: 900;
            color: white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .score-alto {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }

        .score-medio {
            background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
        }

        .score-baixo {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
        }

        .resultado-texto {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 30px;
            margin: 20px 0;
            text-align: left;
        }

        .resultado-texto h3 {
            color: #333;
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        .resultado-texto p {
            color: #666;
            line-height: 1.8;
            margin-bottom: 15px;
        }

        .resultado-texto ul {
            margin-left: 20px;
            color: #666;
            line-height: 1.8;
        }

        .lead-magnet-box {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
            color: white;
            border-radius: 15px;
            padding: 30px;
            margin: 30px 0;
            text-align: center;
        }

        .lead-magnet-box h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .lead-magnet-box p {
            font-size: 1.1em;
            margin-bottom: 25px;
            opacity: 0.95;
        }

        .email-form {
            display: flex;
            gap: 10px;
            margin-bottom: 15px;
            flex-wrap: wrap;
        }

        .email-form input {
            flex: 1;
            min-width: 250px;
            padding: 15px 20px;
            border: none;
            border-radius: 50px;
            font-size: 1em;
        }

        .email-form button {
            background: #fff;
            color: #43e97b;
            padding: 15px 35px;
            border: none;
            border-radius: 50px;
            font-size: 1em;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .email-form button:hover {
            transform: scale(1.05);
        }

        .venda-box {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border-radius: 15px;
            padding: 40px 30px;
            margin: 30px 0;
            text-align: center;
        }

        .venda-box h3 {
            font-size: 2em;
            margin-bottom: 15px;
        }

        .destaque {
            background: rgba(255,255,255,0.2);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .preco-box {
            background: rgba(255,255,255,0.15);
            border-radius: 15px;
            padding: 30px;
            margin: 25px 0;
        }

        .preco-antigo {
            font-size: 1.2em;
            text-decoration: line-through;
            opacity: 0.7;
        }

        .preco-atual {
            font-size: 3em;
            font-weight: 900;
            margin: 15px 0;
        }

        .preco-parcelado {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .beneficios {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .beneficio {
            background: white;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
        }

        .beneficio-icon {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .beneficio h4 {
            color: #333;
            font-size: 1.1em;
            margin-bottom: 5px;
        }

        .beneficio p {
            color: #666;
            font-size: 0.9em;
        }

        .garantia {
            background: rgba(255,255,255,0.2);
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .garantia-icon {
            font-size: 3em;
        }

        .garantia-text {
            text-align: left;
            flex: 1;
        }

        .progress-bar {
            background: #e0e0e0;
            height: 8px;
            border-radius: 10px;
            margin: 20px 0;
            overflow: hidden;
        }

        .progress-fill {
            background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
            height: 100%;
            transition: width 0.3s ease;
        }

        .privacy {
            font-size: 0.85em;
            color: rgba(255,255,255,0.8);
            margin-top: 15px;
        }

        .bonus-list {
            text-align: left;
            list-style: none;
            padding: 0;
            margin: 20px 0;
        }

        .bonus-list li {
            padding: 12px 0;
            border-bottom: 1px solid rgba(255,255,255,0.2);
            display: flex;
            align-items: start;
            gap: 10px;
        }

        .bonus-list li:last-child {
            border-bottom: none;
        }

        .urgencia {
            background: #ff6b6b;
            color: white;
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
            font-weight: 600;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.8; }
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }
            
            .email-form {
                flex-direction: column;
            }
            
            .email-form input {
                min-width: 100%;
            }

            .preco-atual {
                font-size: 2.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🔓 DESTRAVANDO VOCÊ</h1>
            <p>Descubra seu nível de bloqueio em 2 minutos</p>
        </div>

        <div class="content">
            <!-- Seção Introdução -->
            <div class="intro-section active" id="intro">
                <h2>Você Está Travado?</h2>
                <p>Faça o teste rápido e receba seu diagnóstico personalizado + guia gratuito!</p>
                <div class="beneficios">
                    <div class="beneficio">
                        <div class="beneficio-icon">📊</div>
                        <h4>Seu Nível</h4>
                        <p>De bloqueio atual</p>
                    </div>
                    <div class="beneficio">
                        <div class="beneficio-icon">🎯</div>
                        <h4>Áreas Críticas</h4>
                        <p>Que precisam atenção</p>
                    </div>
                    <div class="beneficio">
                        <div class="beneficio-icon">🎁</div>
                        <h4>Guia Grátis</h4>
                        <p>Primeiros passos</p>
                    </div>
                </div>
                <button class="btn" onclick="iniciarQuiz()">FAZER O TESTE GRÁTIS</button>
            </div>

            <!-- Seção Quiz -->
            <div class="quiz-section" id="quiz">
                <div class="progress-bar">
                    <div class="progress-fill" id="progress" style="width: 0%"></div>
                </div>
                <p style="text-align: center; color: #666; margin-bottom: 20px;">
                    Pergunta <span id="current-q">1</span> de 10
                </p>

                <form id="quiz-form">
                    <div class="question">
                        <h3>1. Quando você acorda de manhã, como se sente?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q1" value="3" id="q1a">
                                <label for="q1a">Energizado e motivado para o dia</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q1" value="2" id="q1b">
                                <label for="q1b">Ok, sem muito entusiasmo</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q1" value="1" id="q1c">
                                <label for="q1c">Cansado e sem vontade de fazer nada</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>2. Você tem objetivos claros para os próximos 3 meses?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q2" value="3" id="q2a">
                                <label for="q2a">Sim, e estou trabalhando neles ativamente</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q2" value="2" id="q2b">
                                <label for="q2b">Tenho ideias vagas, mas nada concreto</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q2" value="1" id="q2c">
                                <label for="q2c">Não faço ideia do que quero</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>3. Com que frequência você procrastina tarefas importantes?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q3" value="3" id="q3a">
                                <label for="q3a">Raramente, costumo fazer o que preciso</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q3" value="2" id="q3b">
                                <label for="q3b">Às vezes adio, mas acabo fazendo</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q3" value="1" id="q3c">
                                <label for="q3c">Sempre. Adio tudo até o último minuto</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>4. Como está sua autoestima ultimamente?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q4" value="3" id="q4a">
                                <label for="q4a">Boa! Me sinto capaz e confiante</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q4" value="2" id="q4b">
                                <label for="q4b">Mediana, alguns dias melhor que outros</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q4" value="1" id="q4c">
                                <label for="q4c">Baixa. Me sinto inadequado frequentemente</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>5. Você consegue manter o foco em uma tarefa por mais de 30 minutos?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q5" value="3" id="q5a">
                                <label for="q5a">Sim, consigo focar facilmente</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q5" value="2" id="q5b">
                                <label for="q5b">Com esforço, mas me distraio</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q5" value="1" id="q5c">
                                <label for="q5c">Impossível. Pego o celular a cada 5 minutos</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>6. Como está sua energia física no dia a dia?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q6" value="3" id="q6a">
                                <label for="q6a">Alta! Me sinto disposto</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q6" value="2" id="q6b">
                                <label for="q6b">Razoável, mas canso rápido</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q6" value="1" id="q6c">
                                <label for="q6c">Péssima. Estou sempre exausto</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>7. Você consegue cumprir as promessas que faz para si mesmo?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q7" value="3" id="q7a">
                                <label for="q7a">Sim, na maioria das vezes</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q7" value="2" id="q7b">
                                <label for="q7b">Às vezes sim, às vezes não</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q7" value="1" id="q7c">
                                <label for="q7c">Raramente. Sempre me decepciono</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>8. Como você lida com ansiedade e medo?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q8" value="3" id="q8a">
                                <label for="q8a">Tenho estratégias que funcionam</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q8" value="2" id="q8b">
                                <label for="q8b">Me viro, mas sem muito controle</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q8" value="1" id="q8c">
                                <label for="q8c">Fico paralisado. A ansiedade me domina</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>9. Você se compara frequentemente com outras pessoas?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q9" value="3" id="q9a">
                                <label for="q9a">Raramente. Foco na minha jornada</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q9" value="2" id="q9b">
                                <label for="q9b">Às vezes, principalmente nas redes sociais</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q9" value="1" id="q9c">
                                <label for="q9c">O tempo todo. Sempre acho que não sou bom o suficiente</label>
                            </div>
                        </div>
                    </div>

                    <div class="question">
                        <h3>10. Se pudesse mudar algo na sua vida HOJE, você saberia o quê?</h3>
                        <div class="options">
                            <div class="option">
                                <input type="radio" name="q10" value="3" id="q10a">
                                <label for="q10a">Sim, tenho clareza do que precisa mudar</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q10" value="2" id="q10b">
                                <label for="q10b">Sei que algo precisa mudar, mas não sei exatamente o quê</label>
                            </div>
                            <div class="option">
                                <input type="radio" name="q10" value="1" id="q10c">
                                <label for="q10c">Tudo parece confuso. Não sei por onde começar</label>
                            </div>
                        </div>
                    </div>

                    <button type="button" class="btn" onclick="calcularResultado()">VER MEU RESULTADO</button>
                </form>
            </div>

            <!-- Seção Resultado -->
            <div class="resultado-section" id="resultado">
                <h2 style="color: #333; margin-bottom: 20px;">Seu Resultado:</h2>
                <div class="score-circle" id="score-circle">
                    <span id="score-text">0</span>
                </div>
                
                <div class="resultado-texto" id="resultado-texto"></div>

                <!-- Lead Magnet Grátis -->
                <div class="lead-magnet-box">
                    <h3>🎁 RECEBA SEU GUIA GRÁTIS</h3>
                    <p><strong>"Os 5 Primeiros Passos Para Se Destravar"</strong></p>
                    <p>PDF exclusivo com técnicas práticas baseadas no seu resultado</p>
                    
                    <div class="email-form">
                        <input type="email" id="email-lead" placeholder="Seu melhor e-mail" required>
                        <button type="button" onclick="baixarGuiaGratis()">QUERO O GUIA!</button>
                    </div>
                    
                    <p class="privacy">🔒 Seus dados estão seguros. Sem spam.</p>
                </div>

                <!-- Oferta do Ebook Completo -->
                <div class="venda-box">
                    <div class="urgencia">
                        ⏰ OFERTA ESPECIAL: Desconto de 50% por tempo limitado!
                    </div>

                    <h3>📚 EBOOK COMPLETO "DESTRAVANDO VOCÊ"</h3>
                    <p style="font-size: 1.2em; margin-bottom: 25px;">O sistema completo de transformação que já ajudou centenas de pessoas a saírem do estado de bloqueio</p>

                    <div class="preco-box">
                        <div class="preco-antigo">De R$ 97,00</div>
                        <div class="preco-atual">R$ 47,00</div>
                        <div class="preco-parcelado">ou 12x de R$ 4,60</div>
                    </div>

                    <div class="destaque">
                        <h4 style="margin-bottom: 15px; font-size: 1.3em;">✨ O QUE VOCÊ VAI RECEBER:</h4>
                        <ul class="bonus-list">
                            <li><span style="font-size: 1.3em;">📖</span> <strong>Ebook Completo (150+ páginas)</strong> - Todo o método passo a passo</li>
                            <li><span style="font-size: 1.3em;">🎯</span> <strong>Sistema 3×3×3</strong> - Foco e disciplina que funciona</li>
                            <li><span style="font-size: 1.3em;">📅</span> <strong>Plano de 30 Dias</strong> - Cronograma diário detalhado</li>
                            <li><span style="font-size: 1.3em;">📝</span> <strong>Planner Digital</strong> - Templates prontos em PDF</li>
                            <li><span style="font-size: 1.3em;">🎁</span> <strong>BÔNUS 1:</strong> Workbook com 50+ exercícios práticos</li>
                            <li><span style="font-size: 1.3em;">🎁</span> <strong>BÔNUS 2:</strong> Checklist de hábitos diários</li>
                            <li><span style="font-size: 1.3em;">🎁</span> <strong>BÔNUS 3:</strong> Guia rápido "Reset Mental em 5min"</li>
                        </ul>
                    </div>

                    <div class="garantia">
                        <div class="garantia-icon">🛡️</div>
                        <div class="garantia-text">
                            <strong style="font-size: 1.2em;">Garantia de 7 Dias</strong>
                            <p style="margin: 5px 0 0 0;">Se você não gostar ou não ver resultados, devolvemos 100% do seu dinheiro. Sem perguntas.</p>
                        </div>
                    </div>

                    <button class="btn" onclick="comprarEbook()" style="font-size: 1.3em; padding: 20px 40px; margin-top: 25px;">
                        🔥 QUERO ME DESTRAVAR AGORA
                    </button>

                    <p style="margin-top: 20px; font-size: 0.9em; opacity: 0.9;">
                        💳 Pagamento 100% seguro | Acesso imediato após confirmação
                    </p>
                </div>

                <div style="background: #f8f9fa; border-radius: 15px; padding: 30px; margin-top: 30px;">
                    <h3 style="color: #333; margin-bottom: 20px; text-align: center;">❓ Ainda com dúvidas?</h3>
                    <div style="text-align: left; color: #666;">
                        <p style="margin-bottom: 15px;"><strong>P: O ebook é só teoria ou tem práticas reais?</strong></p>
                        <p style="margin-bottom: 25px;">R: É 80% prático! Cada capítulo tem exercícios, checklists e técnicas para aplicar imediatamente.</p>

                        <p style="margin-bottom: 15px;"><strong>P: Funciona para qualquer pessoa?</strong></p>
                        <p style="margin-bottom: 25px;">R: Sim! Se você se sente travado em qualquer área da vida (carreira, relacionamentos, saúde, finanças), o método funciona.</p>

                        <p style="margin-bottom: 15px;"><strong>P: Quanto tempo leva para ver resultados?</strong></p>
                        <p style="margin-bottom: 25px;">R: As primeiras mudanças aparecem em 7 dias. A transformação completa acontece seguindo o plano de 30 dias.</p>

                        <p style="margin-bottom: 15px;"><strong>P: E se eu não tiver tempo?</strong></p>
                        <p>R: O sistema foi criado para quem tem pouco tempo. Você precisa de apenas 15-30 minutos por dia.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function iniciarQuiz() {
