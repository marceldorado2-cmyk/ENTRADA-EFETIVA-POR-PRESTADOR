<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Entrada Efetiva — Collina Dreams</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.7/dist/chart.umd.min.js"></script>
    <style>
        :root {
            --bg-deep: #050510;
            --bg-card: rgba(10, 14, 28, 0.85);
            --border-glow: rgba(100, 120, 255, 0.25);
            --accent-cyan: #00e5ff;
            --accent-purple: #b44dff;
            --accent-pink: #ff3d7f;
            --accent-green: #00e676;
            --accent-amber: #ffb300;
            --text-primary: #e8eaf6;
            --text-secondary: #9fa8da;
            --text-muted: #5c6a9e;
            --glass-bg: rgba(15, 20, 40, 0.7);
            --glass-border: rgba(120, 140, 255, 0.18);
            --radius-lg: 20px;
            --radius-md: 14px;
            --radius-sm: 10px;
            --shadow-glow: 0 0 30px rgba(100, 120, 255, 0.12);
            --transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background: var(--bg-deep);
            background-image:
                radial-gradient(ellipse at 20% 10%, rgba(100, 80, 255, 0.08) 0%, transparent 60%),
                radial-gradient(ellipse at 75% 20%, rgba(0, 229, 255, 0.06) 0%, transparent 55%),
                radial-gradient(ellipse at 50% 80%, rgba(180, 77, 255, 0.05) 0%, transparent 50%);
            font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
            color: var(--text-primary);
            min-height: 100vh;
            padding: 24px;
            -webkit-font-smoothing: antialiased;
        }

        .dashboard {
            max-width: 1560px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 16px;
            margin-bottom: 28px;
        }

        .header-brand {
            display: flex;
            align-items: center;
            gap: 14px;
        }

        .logo-icon {
            width: 48px;
            height: 48px;
            border-radius: var(--radius-sm);
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-cyan));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 22px;
            font-weight: 800;
            color: #fff;
            box-shadow: 0 0 24px rgba(150, 100, 255, 0.4);
            letter-spacing: -1px;
        }

        .title-block h1 {
            font-size: 26px;
            font-weight: 700;
            background: linear-gradient(135deg, #e8eaf6, #b0bfff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            letter-spacing: -0.5px;
        }

        .title-block span {
            font-size: 13px;
            color: var(--text-muted);
            letter-spacing: 1.5px;
            text-transform: uppercase;
            font-weight: 500;
        }

        .header-meta {
            display: flex;
            gap: 14px;
            align-items: center;
        }

        .status-badge {
            padding: 8px 18px;
            border-radius: 30px;
            font-size: 13px;
            font-weight: 600;
            letter-spacing: 0.5px;
            border: 1px solid rgba(0, 230, 118, 0.4);
            background: rgba(0, 230, 118, 0.08);
            color: var(--accent-green);
            display: flex;
            align-items: center;
            gap: 7px;
        }

        .status-badge::before {
            content: '';
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background: var(--accent-green);
            box-shadow: 0 0 8px var(--accent-green);
            animation: pulse-dot 2s infinite;
        }

        @keyframes pulse-dot {
            0%, 100% { box-shadow: 0 0 6px var(--accent-green); }
            50% { box-shadow: 0 0 16px var(--accent-green), 0 0 28px rgba(0, 230, 118, 0.5); }
        }

        .filter-bar {
            background: var(--glass-bg);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            border-radius: var(--radius-lg);
            padding: 18px 22px;
            display: flex;
            gap: 14px;
            flex-wrap: wrap;
            align-items: center;
            margin-bottom: 24px;
            box-shadow: var(--shadow-glow);
        }

        .filter-bar label {
            font-size: 11px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: var(--text-muted);
            font-weight: 600;
        }

        .filter-bar select,
        .filter-bar input {
            background: rgba(20, 25, 50, 0.8);
            border: 1px solid var(--border-glow);
            color: var(--text-primary);
            padding: 10px 14px;
            border-radius: var(--radius-sm);
            font-size: 13px;
            font-family: inherit;
            transition: var(--transition);
            outline: none;
            min-width: 150px;
        }

        .filter-bar select:hover,
        .filter-bar input:hover {
            border-color: var(--accent-cyan);
            box-shadow: 0 0 12px rgba(0, 229, 255, 0.15);
        }

        .filter-bar select:focus,
        .filter-bar input:focus {
            border-color: var(--accent-purple);
            box-shadow: 0 0 16px rgba(180, 77, 255, 0.2);
        }

        .filter-bar select option {
            background: #141932;
            color: #e8eaf6;
        }

        .btn-reset {
            background: transparent;
            border: 1px solid rgba(255, 61, 127, 0.4);
            color: var(--accent-pink);
            padding: 10px 20px;
            border-radius: var(--radius-sm);
            cursor: pointer;
            font-weight: 600;
            font-size: 12px;
            letter-spacing: 1px;
            text-transform: uppercase;
            transition: var(--transition);
            font-family: inherit;
        }

        .btn-reset:hover {
            background: rgba(255, 61, 127, 0.1);
            box-shadow: 0 0 16px rgba(255, 61, 127, 0.2);
        }

        .kpi-row {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 18px;
            margin-bottom: 24px;
        }

        .kpi-card {
            background: var(--bg-card);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            border-radius: var(--radius-lg);
            padding: 22px 24px;
            position: relative;
            overflow: hidden;
            box-shadow: var(--shadow-glow);
            transition: var(--transition);
        }

        .kpi-card:hover {
            transform: translateY(-2px);
            border-color: var(--border-glow);
            box-shadow: 0 0 40px rgba(100, 120, 255, 0.2);
        }

        .kpi-card::after {
            content: '';
            position: absolute;
            top: -40px;
            right: -40px;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            opacity: 0.06;
            pointer-events: none;
        }

        .kpi-card.total::after { background: var(--accent-cyan); }
        .kpi-card.entrada::after { background: var(--accent-green); }
        .kpi-card.percent::after { background: var(--accent-purple); }
        .kpi-card.ativos::after { background: var(--accent-amber); }
        .kpi-card.cancelados::after { background: var(--accent-pink); }

        .kpi-label {
            font-size: 11px;
            text-transform: uppercase;
            letter-spacing: 1.8px;
            color: var(--text-muted);
            font-weight: 600;
            margin-bottom: 6px;
        }

        .kpi-value {
            font-size: 30px;
            font-weight: 800;
            letter-spacing: -1px;
        }

        .kpi-value.cyan {
            background: linear-gradient(135deg, #00e5ff, #84ffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .kpi-value.green {
            background: linear-gradient(135deg, #00e676, #69f0ae);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .kpi-value.purple {
            background: linear-gradient(135deg, #b44dff, #ea80fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .kpi-value.amber {
            background: linear-gradient(135deg, #ffb300, #ffe57f);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .kpi-value.pink {
            background: linear-gradient(135deg, #ff3d7f, #ff80ab);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .kpi-sub {
            font-size: 12px;
            color: var(--text-muted);
            margin-top: 4px;
        }

        .charts-row {
            display: grid;
            grid-template-columns: 1.3fr 1fr;
            gap: 18px;
            margin-bottom: 24px;
        }

        @media (max-width: 1100px) {
            .charts-row { grid-template-columns: 1fr; }
        }

        .chart-panel {
            background: var(--bg-card);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            border-radius: var(--radius-lg);
            padding: 22px;
            box-shadow: var(--shadow-glow);
            position: relative;
        }

        .chart-panel h3 {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: var(--text-secondary);
            margin-bottom: 16px;
            font-weight: 600;
        }

        .chart-wrap {
            position: relative;
            width: 100%;
        }

        .chart-wrap canvas {
            width: 100% !important;
        }

        .charts-row-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 18px;
            margin-bottom: 24px;
        }

        @media (max-width: 900px) {
            .charts-row-2 { grid-template-columns: 1fr; }
        }

        .table-panel {
            background: var(--bg-card);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            border-radius: var(--radius-lg);
            padding: 22px;
            box-shadow: var(--shadow-glow);
            overflow: hidden;
        }

        .table-panel h3 {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: var(--text-secondary);
            margin-bottom: 14px;
            font-weight: 600;
        }

        .table-scroll {
            overflow-x: auto;
            border-radius: var(--radius-sm);
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 12px;
            min-width: 1000px;
        }

        thead th {
            background: rgba(20, 25, 50, 0.9);
            color: var(--text-muted);
            font-weight: 700;
            padding: 12px 14px;
            text-align: left;
            font-size: 10px;
            letter-spacing: 1.2px;
            text-transform: uppercase;
            border-bottom: 1px solid var(--border-glow);
            white-space: nowrap;
        }

        tbody td {
            padding: 11px 14px;
            border-bottom: 1px solid rgba(60, 70, 110, 0.15);
            color: var(--text-primary);
            white-space: nowrap;
        }

        tbody tr {
            transition: var(--transition);
        }

        tbody tr:hover {
            background: rgba(100, 120, 255, 0.05);
        }

        .badge-status {
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 10px;
            font-weight: 700;
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        .badge-ativo {
            background: rgba(0, 230, 118, 0.15);
            color: var(--accent-green);
            border: 1px solid rgba(0, 230, 118, 0.3);
        }

        .badge-cancelado {
            background: rgba(255, 61, 127, 0.12);
            color: var(--accent-pink);
            border: 1px solid rgba(255, 61, 127, 0.3);
        }

        .no-data {
            text-align: center;
            padding: 40px;
            color: var(--text-muted);
            font-style: italic;
        }

        ::-webkit-scrollbar {
            height: 6px;
            width: 6px;
        }

        ::-webkit-scrollbar-track {
            background: transparent;
        }

        ::-webkit-scrollbar-thumb {
            background: rgba(100, 120, 255, 0.3);
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: rgba(100, 120, 255, 0.5);
        }

        @media (max-width: 768px) {
            body { padding: 12px; }
            .header {
                flex-direction: column;
                align-items: flex-start;
            }
            .kpi-value { font-size: 24px; }
            .filter-bar {
                flex-direction: column;
                align-items: stretch;
            }
            .filter-bar select,
            .filter-bar input {
                width: 100%;
                min-width: unset;
            }
        }
    </style>
</head>
<body>
    <div class="dashboard">
        <div class="header">
            <div class="header-brand">
                <div class="logo-icon">CD</div>
                <div class="title-block">
                    <h1>Entrada Efetiva · Collina Dreams</h1>
                    <span>Dashboard Comercial — Junho 2026</span>
                </div>
            </div>
            <div class="header-meta">
                <div class="status-badge">Dados Atualizados</div>
                <span style="color:var(--text-muted);font-size:12px;">Período: 01/06 a 25/06/2026</span>
            </div>
        </div>

        <div class="filter-bar">
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Data Início</label>
                <input type="date" id="filterDateStart" value="2026-06-01">
            </div>
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Data Fim</label>
                <input type="date" id="filterDateEnd" value="2026-06-30">
            </div>
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Closer</label>
                <select id="filterCloser"><option value="">Todos</option></select>
            </div>
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Liner</label>
                <select id="filterLiner"><option value="">Todos</option></select>
            </div>
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Promotor</label>
                <select id="filterPromotor"><option value="">Todos</option></select>
            </div>
            <div style="display:flex;flex-direction:column;gap:4px;">
                <label>Status</label>
                <select id="filterStatus">
                    <option value="">Todos</option>
                    <option value="ATIVO">Ativo</option>
                    <option value="CANCELADO">Cancelado</option>
                </select>
            </div>
            <button class="btn-reset" onclick="resetFilters()">⟳ Limpar Filtros</button>
        </div>

        <div class="kpi-row" id="kpiRow"></div>

        <div class="charts-row">
            <div class="chart-panel">
                <h3>📊 Entrada Efetiva por Closer</h3>
                <div class="chart-wrap"><canvas id="chartCloser"></canvas></div>
            </div>
            <div class="chart-panel">
                <h3>🥧 Distribuição por Status</h3>
                <div class="chart-wrap" style="max-width:320px;margin:0 auto;"><canvas id="chartStatus"></canvas></div>
            </div>
        </div>

        <div class="charts-row-2">
            <div class="chart-panel">
                <h3>📈 Entrada Efetiva por Dia</h3>
                <div class="chart-wrap"><canvas id="chartDaily"></canvas></div>
            </div>
            <div class="chart-panel">
                <h3>👤 Entrada Efetiva por Promotor</h3>
                <div class="chart-wrap"><canvas id="chartPromotor"></canvas></div>
            </div>
        </div>

        <div class="table-panel">
            <h3>📋 Detalhamento Completo <span style="color:var(--text-muted);font-weight:400;font-size:11px;" id="tableCount"></span></h3>
            <div class="table-scroll">
                <table>
                    <thead>
                        <tr>
                            <th>Data</th>
                            <th>Contrato</th>
                            <th>Cessionário</th>
                            <th>Valor Negociado</th>
                            <th>Status</th>
                            <th>Promotor</th>
                            <th>Liner</th>
                            <th>Closer</th>
                            <th>Total Entrada</th>
                            <th>Entrada Efetiva</th>
                            <th>% Efetivo</th>
                        </tr>
                    </thead>
                    <tbody id="tableBody"></tbody>
                </table>
            </div>
        </div>
    </div>

    <script>
        const rawData = [
            { dt: '2026-06-01', contrato: 'COLLINA - 17/26', cliente: 'GUSTAVO TALLES DA SILVA', valor: 88000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 19000, efetiva: 1900 },
            { dt: '2026-06-01', contrato: 'COLLINA - 17/38', cliente: 'GUSTAVO TALLES DA SILVA', valor: 88000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 19000, efetiva: 1900 },
            { dt: '2026-06-02', contrato: 'COLLINA - 17/08', cliente: 'FRANCISCO DE ASSIS AMARO DE SOUZA', valor: 90000,
              status: 'CANCELADO', promotor: 'LARISSA RIBEIRO', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 0, efetiva: 0 },
            { dt: '2026-06-02', contrato: 'COLLINA - 17/14', cliente: 'ROSILEY DO CARMO NASCIMENTO', valor: 90000,
              status: 'ATIVO', promotor: 'RENAN MARCONDES JOHAS', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-02', contrato: 'COLLINA - 16/34', cliente: 'ALLAN NONATO RODRIGUES DE SOUSA', valor: 90000,
              status: 'ATIVO', promotor: 'PEDRO HENRIQUE GOMES SANTOS', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 1500 },
            { dt: '2026-06-02', contrato: 'COLLINA - 17/11', cliente: 'ALLAN NONATO RODRIGUES DE SOUSA', valor: 90000,
              status: 'ATIVO', promotor: 'PEDRO HENRIQUE GOMES SANTOS', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 1500 },
            { dt: '2026-06-02', contrato: 'COLLINA - 02/28', cliente: 'EDSON MARQUES DOS SANTOS JUNIOR', valor: 89000,
              status: 'CANCELADO', promotor: 'ALEXANDRE PASQUALE JUNIOR', liner: 'RENAN FAGLIARI LOURENCO', closer: 'JOSE NETO',
              entrada: 600, efetiva: 600 },
            { dt: '2026-06-02', contrato: 'COLLINA - 06/16', cliente: 'EDSON MARQUES DOS SANTOS JUNIOR', valor: 89000,
              status: 'CANCELADO', promotor: 'ALEXANDRE PASQUALE JUNIOR', liner: 'RENAN FAGLIARI LOURENCO', closer: 'JOSE NETO',
              entrada: 600, efetiva: 600 },
            { dt: '2026-06-02', contrato: 'COLLINA - 11/50', cliente: 'ROBERTO MAURO DA SILVA', valor: 98000, status: 'ATIVO',
              promotor: 'RENAN MARCONDES JOHAS', liner: 'STELLA CHRISTY DIAS', closer: 'BIANCA SANTOS', entrada: 19600,
              efetiva: 653.33 },
            { dt: '2026-06-03', contrato: 'COLLINA - 17/19', cliente: 'VITOR DANIEL SILVA CASTANHEIRA', valor: 90000,
              status: 'ATIVO', promotor: 'ADRIANO MOREIRA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 1000 },
            { dt: '2026-06-03', contrato: 'COLLINA - 13/41', cliente: 'VITOR DANIEL SILVA CASTANHEIRA', valor: 90000,
              status: 'ATIVO', promotor: 'ADRIANO MOREIRA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 1000 },
            { dt: '2026-06-04', contrato: 'COLLINA - 17/34', cliente: 'CELINA MARIA ALVES BASTOS', valor: 91830,
              status: 'CANCELADO', promotor: 'FELIPE DA SILVA RIBEIRO', liner: 'BIANCA DUARTE', closer: 'JOSE NETO',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-04', contrato: 'COLLINA - 13/03', cliente: 'LEONARDO RODRIGUES GALHARDE', valor: 90000,
              status: 'ATIVO', promotor: 'LARISSA RIBEIRO', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'JOSE NETO',
              entrada: 17999.82, efetiva: 300 },
            { dt: '2026-06-04', contrato: 'COLLINA - 03/38', cliente: 'LEONARDO RODRIGUES GALHARDE', valor: 90000,
              status: 'ATIVO', promotor: 'LARISSA RIBEIRO', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'JOSE NETO',
              entrada: 17999.82, efetiva: 300 },
            { dt: '2026-06-04', contrato: 'COLLINA - 16/47', cliente: 'LUCIANO VALERAS DOS SANTOS', valor: 82000,
              status: 'ATIVO', promotor: 'FELIPE DA SILVA RIBEIRO', liner: 'RENATA DORADO', closer: 'BIANCA SANTOS',
              entrada: 16400, efetiva: 1640 },
            { dt: '2026-06-04', contrato: 'COLLINA - 13/46', cliente: 'LUCIANO VALERAS DOS SANTOS', valor: 82000,
              status: 'ATIVO', promotor: 'FELIPE DA SILVA RIBEIRO', liner: 'RENATA DORADO', closer: 'BIANCA SANTOS',
              entrada: 16400, efetiva: 1640 },
            { dt: '2026-06-04', contrato: 'COLLINA - 06/22', cliente: 'LUCIANO VALERAS DOS SANTOS', valor: 82000,
              status: 'ATIVO', promotor: 'FELIPE DA SILVA RIBEIRO', liner: 'RENATA DORADO', closer: 'BIANCA SANTOS',
              entrada: 16399.84, efetiva: 1640 },
            { dt: '2026-06-04', contrato: 'COLLINA - 06/23', cliente: 'LUCIANO VALERAS DOS SANTOS', valor: 82000,
              status: 'ATIVO', promotor: 'FELIPE DA SILVA RIBEIRO', liner: 'RENATA DORADO', closer: 'BIANCA SANTOS',
              entrada: 16399.84, efetiva: 1640 },
            { dt: '2026-06-04', contrato: 'COLLINA - 13/42', cliente: 'GABRIELLY SANTOS MUNHOZ GIMENES', valor: 98000,
              status: 'CANCELADO', promotor: 'IVANILSON LUIZ AGUIAR LIMA', liner: 'STELLA CHRISTY DIAS', closer: 'BIANCA SANTOS',
              entrada: 0, efetiva: 0 },
            { dt: '2026-06-05', contrato: 'COLLINA - 22/21', cliente: 'FABIO JUNQUEIRA ESTEVES', valor: 92000, status: 'ATIVO',
              promotor: 'ANA CAROLINE', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS', entrada: 18400,
              efetiva: 7500 },
            { dt: '2026-06-05', contrato: 'COLLINA - 22/22', cliente: 'FABIO JUNQUEIRA ESTEVES', valor: 92000, status: 'ATIVO',
              promotor: 'ANA CAROLINE', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS', entrada: 18400,
              efetiva: 7500 },
            { dt: '2026-06-05', contrato: 'COLLINA - 20/47', cliente: 'MAXI EMILIANO OLIVEIRA MOREIRA', valor: 85000,
              status: 'CANCELADO', promotor: 'JESSICA BARBOSA', liner: 'AMANDA DORADO', closer: 'AMANDA DORADO',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-05', contrato: 'COLLINA - 22/48', cliente: 'MAXI EMILIANO OLIVEIRA MOREIRA', valor: 85000,
              status: 'CANCELADO', promotor: 'JESSICA BARBOSA', liner: 'AMANDA DORADO', closer: 'AMANDA DORADO',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-05', contrato: 'COLLINA - 23/39', cliente: 'MAXI EMILIANO OLIVEIRA MOREIRA', valor: 85000,
              status: 'CANCELADO', promotor: 'JESSICA BARBOSA', liner: 'AMANDA DORADO', closer: 'AMANDA DORADO',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-05', contrato: 'COLLINA - 02/47', cliente: 'MAXI EMILIANO OLIVEIRA MOREIRA', valor: 85000,
              status: 'CANCELADO', promotor: 'JESSICA BARBOSA', liner: 'AMANDA DORADO', closer: 'AMANDA DORADO',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-05', contrato: 'COLLINA- 04/05', cliente: 'LEONARDO TIMOTE', valor: 90000, status: 'CANCELADO',
              promotor: 'DANIELA MOURA', liner: 'JUNIOR PEREIRA', closer: 'LUIS ALVES DO AMARAL NETO', entrada: 2000,
              efetiva: 2000 },
            { dt: '2026-06-05', contrato: 'COLLINA - 05/05', cliente: 'LAURA GODOY DA SILVA', valor: 88000, status: 'ATIVO',
              promotor: 'JOSYENE FREITAS', liner: 'RENAN FAGLIARI LOURENCO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 17600, efetiva: 1760 },
            { dt: '2026-06-05', contrato: 'COLLINA- 04/13', cliente: 'LAURA GODOY DA SILVA', valor: 88000, status: 'ATIVO',
              promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO', entrada: 17600,
              efetiva: 1760 },
            { dt: '2026-06-05', contrato: 'COLLINA - 05/47', cliente: 'VALMIR BENTO DA SILVA', valor: 90000,
              status: 'CANCELADO', promotor: 'IVANILSON LUIZ AGUIAR LIMA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 1500, efetiva: 1500 },
            { dt: '2026-06-05', contrato: 'COLLINA - 05/12', cliente: 'CARLA TATIANE AMORIM CORREIA DE CARVALHO',
              valor: 90000, status: 'CANCELADO', promotor: 'ALEXANDRE PASQUALE JUNIOR', liner: 'THAMIRES FERNANDES MOREIRA',
              closer: 'RENATA BUENO', entrada: 0, efetiva: 0 },
            { dt: '2026-06-05', contrato: 'COLLINA - 11/14', cliente: 'NARAIANE LETICIA FERREIRA', valor: 98000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'ALEX DE MENDES BRITO', closer: 'RUTEMBERG CORREIA',
              entrada: 19600, efetiva: 1000 },
            { dt: '2026-06-05', contrato: 'COLLINA - 05/24', cliente: 'NARAIANE LETICIA FERREIRA', valor: 98000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'ALEX DE MENDES BRITO', closer: 'RUTEMBERG CORREIA',
              entrada: 19600, efetiva: 1000 },
            { dt: '2026-06-06', contrato: 'COLLINA - 22/15', cliente: 'KEITY MIRANDA DOS SANTOS', valor: 90000,
              status: 'CANCELADO', promotor: 'ANA CAROLINE', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'JOSE NETO',
              entrada: 0, efetiva: 0 },
            { dt: '2026-06-06', contrato: 'COLLINA - 22/31', cliente: 'MARCELO GAMA CORREA MARTINS', valor: 87000,
              status: 'ATIVO', promotor: 'RICARDO MALTCHIK', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 17400, efetiva: 1740 },
            { dt: '2026-06-06', contrato: 'COLLINA - 22/45', cliente: 'MARCELO GAMA CORREA MARTINS', valor: 87000,
              status: 'ATIVO', promotor: 'RICARDO MALTCHIK', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 17400, efetiva: 1740 },
            { dt: '2026-06-06', contrato: 'COLLINA - 05/19', cliente: 'MARCELO DE AZEVEDO MARQUES', valor: 90000,
              status: 'ATIVO', promotor: 'MARCIO ALFAIA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 18000, efetiva: 1800 },
            { dt: '2026-06-06', contrato: 'COLLINA - 05/01', cliente: 'ALEXSANDRO FREITAS DA SILVA', valor: 85000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 17000.08, efetiva: 600 },
            { dt: '2026-06-06', contrato: 'COLLINA - 02/29', cliente: 'ALEXSANDRO FREITAS DA SILVA', valor: 85000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 17000.08, efetiva: 600 },
            { dt: '2026-06-07', contrato: 'COLLINA - 03/02', cliente: 'GABRIELA GONCALVES', valor: 90000, status: 'CANCELADO',
              promotor: 'ALEXANDRE PASQUALE JUNIOR', liner: 'RENATA DORADO', closer: 'JOSE NETO', entrada: 600,
              efetiva: 600 },
            { dt: '2026-06-07', contrato: 'COLLINA - 07/19', cliente: 'CAROLINA GOMES PEREIRA SANTANA', valor: 87000,
              status: 'ATIVO', promotor: 'JESSICA BARBOSA', liner: 'RENAN FAGLIARI LOURENCO', closer: 'DANIEL MARCOS',
              entrada: 17400, efetiva: 580 },
            { dt: '2026-06-08', contrato: 'COLLINA - 05/20', cliente: 'MIRIAM ALBINO DE OLIVEIRA', valor: 90000,
              status: 'ATIVO', promotor: 'ADRIANO MOREIRA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA',
              entrada: 17999.84, efetiva: 3600 },
            { dt: '2026-06-08', contrato: 'COLLINA - 03/10', cliente: 'LETICIA SILVA GONCALVES', valor: 88000,
              status: 'ATIVO', promotor: 'MATHEUS DOMINGOS SANTOS', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 17599.96, efetiva: 2640 },
            { dt: '2026-06-10', contrato: 'COLLINA - 07/17', cliente: 'MARIA RAQUEL FERREIRA', valor: 95000, status: 'ATIVO',
              promotor: 'REBECA BRAGA PINTO', liner: 'ALEX DE MENDES BRITO', closer: 'DANIEL MARCOS', entrada: 19000,
              efetiva: 6000 },
            { dt: '2026-06-11', contrato: 'COLLINA - 22/30', cliente: 'ERNANDO DOS SANTOS SOUSA NETO', valor: 90000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-11', contrato: 'COLLINA - 10/50', cliente: 'ERNANDO DOS SANTOS SOUSA NETO', valor: 90000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-11', contrato: 'COLLINA - 10/28', cliente: 'FRANCISCO EUGENIO SIQUEIRA LIMA', valor: 90000,
              status: 'CANCELADO', promotor: 'RICARDO MALTCHIK', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'RENATA BUENO',
              entrada: 620, efetiva: 620 },
            { dt: '2026-06-11', contrato: 'COLLINA - 10/45', cliente: 'JORDANA FERREIRA DA CONCEICAO RIBEIRO', valor: 98000,
              status: 'ATIVO', promotor: 'IVANILSON LUIZ AGUIAR LIMA', liner: 'STELLA CHRISTY DIAS', closer: 'BIANCA SANTOS',
              entrada: 19599.9, efetiva: 2613.32 },
            { dt: '2026-06-12', contrato: 'COLLINA - 06/50',
              cliente: 'ALINE SUZANA CAMARGO DA SILVA CRUZ ALFERES', valor: 92000, status: 'ATIVO',
              promotor: 'ADRIANO MOREIRA', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS', entrada: 18399.91,
              efetiva: 1840 },
            { dt: '2026-06-12', contrato: 'COLLINA - 10/49', cliente: 'MICHELLE EUSTAQUIO BUENO', valor: 90000,
              status: 'ATIVO', promotor: 'JONATAS FRANÇA DA SILVA', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-12', contrato: 'COLLINA - 20/10', cliente: 'MICHELLE EUSTAQUIO BUENO', valor: 90000,
              status: 'ATIVO', promotor: 'JONATAS FRANÇA DA SILVA', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-12', contrato: 'COLLINA - 03/43', cliente: 'JOMECI SANTANA BARBOSA', valor: 90000,
              status: 'CANCELADO', promotor: 'DANIELA MOURA', liner: 'KARINA FONTAN NASCIMENTO', closer: 'JOSE NETO',
              entrada: 600, efetiva: 600 },
            { dt: '2026-06-13', contrato: 'COLLINA - 02/03', cliente: 'ADRIANA MEDEIROS PEREIRA', valor: 90000,
              status: 'CANCELADO', promotor: 'IVANILSON LUIZ AGUIAR LIMA', liner: 'ALEX DE MENDES BRITO', closer: 'RUTEMBERG CORREIA',
              entrada: 1800, efetiva: 1800 },
            { dt: '2026-06-13', contrato: 'COLLINA - 10/40', cliente: 'TAINA RAMOS', valor: 90000, status: 'CANCELADO',
              promotor: 'JONATAS FRANÇA DA SILVA', liner: 'BIANCA DUARTE', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 3600, efetiva: 3600 },
            { dt: '2026-06-13', contrato: 'COLLINA - 20/03', cliente: 'TAINA RAMOS', valor: 90000, status: 'CANCELADO',
              promotor: 'JONATAS FRANÇA DA SILVA', liner: 'BIANCA DUARTE', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 3600, efetiva: 3600 },
            { dt: '2026-06-13', contrato: 'COLLINA - 26/45', cliente: 'FERNANDO SARGACO DA COSTA E SILVA', valor: 125000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 25000, efetiva: 2500 },
            { dt: '2026-06-13', contrato: 'COLLINA - 32/10', cliente: 'FERNANDO SARGACO DA COSTA E SILVA', valor: 125000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 25000, efetiva: 2500 },
            { dt: '2026-06-15', contrato: 'COLLINA - 03/13', cliente: 'ESTER DE CAMARGO OCTAVIANO', valor: 90000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'JUNIOR PEREIRA', closer: 'RENATA BUENO',
              entrada: 18000.01, efetiva: 400 },
            { dt: '2026-06-15', contrato: 'COLLINA - 07/51', cliente: 'ESTER DE CAMARGO OCTAVIANO', valor: 90000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'JUNIOR PEREIRA', closer: 'RENATA BUENO',
              entrada: 18000.01, efetiva: 400 },
            { dt: '2026-06-16', contrato: 'COLLINA- 04/02', cliente: 'RITA DE CASSIA ROCHA DE ABREU', valor: 79000,
              status: 'ATIVO', promotor: 'JONATAS FRANÇA DA SILVA', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 15799.99, efetiva: 1579.99 },
            { dt: '2026-06-16', contrato: 'COLLINA- 04/06', cliente: 'RITA DE CASSIA ROCHA DE ABREU', valor: 79000,
              status: 'ATIVO', promotor: 'JONATAS FRANÇA DA SILVA', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 15799.99, efetiva: 1579.99 },
            { dt: '2026-06-16', contrato: 'COLLINA - 14/41', cliente: 'MONIQUE PEREIRA SILVA', valor: 80000, status: 'ATIVO',
              promotor: 'JOSE ADEMIR SILVA TAVARES', liner: 'STELLA CHRISTY DIAS', closer: 'JOSE NETO', entrada: 16000,
              efetiva: 533.5 },
            { dt: '2026-06-16', contrato: 'COLLINA - 15/10', cliente: 'MONIQUE PEREIRA SILVA', valor: 80000, status: 'ATIVO',
              promotor: 'JOSE ADEMIR SILVA TAVARES', liner: 'STELLA CHRISTY DIAS', closer: 'JOSE NETO', entrada: 16000,
              efetiva: 533.5 },
            { dt: '2026-06-16', contrato: 'COLLINA - 06/04', cliente: 'MAYCON PERROTTA MAIA', valor: 92700,
              status: 'CANCELADO', promotor: 'JOSE ADEMIR SILVA TAVARES', liner: 'STELLA CHRISTY DIAS', closer: 'JOSE NETO',
              entrada: 618, efetiva: 618 },
            { dt: '2026-06-17', contrato: 'COLLINA - 22/36', cliente: 'IZABEL CARVALHO NICOLAU', valor: 90000, status: 'ATIVO',
              promotor: 'DANIELA MOURA', liner: 'RUTEMBERG CORREIA', closer: 'RUTEMBERG CORREIA', entrada: 18000,
              efetiva: 18000 },
            { dt: '2026-06-18', contrato: 'COLLINA - 22/11', cliente: 'LUIZ AUGUSTO SILVA DOS SANTOS', valor: 98000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'DANIEL MARCOS',
              entrada: 19599.84, efetiva: 3176.55 },
            { dt: '2026-06-18', contrato: 'COLLINA - 15/39', cliente: 'LAIS FASSONI RIBEIRO DESOTTI', valor: 89000,
              status: 'ATIVO', promotor: 'RENAN MARCONDES JOHAS', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 17799.88, efetiva: 8405 },
            { dt: '2026-06-18', contrato: 'COLLINA - 12/01', cliente: 'LAIS FASSONI RIBEIRO DESOTTI', valor: 89000,
              status: 'ATIVO', promotor: 'RENAN MARCONDES JOHAS', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 17799.88, efetiva: 8405 },
            { dt: '2026-06-18', contrato: 'COLLINA - 17/08', cliente: 'LAIS FASSONI RIBEIRO DESOTTI', valor: 89000,
              status: 'ATIVO', promotor: 'RENAN MARCONDES JOHAS', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 17799.88, efetiva: 8405 },
            { dt: '2026-06-18', contrato: 'COLLINA - 13/42', cliente: 'LAIS FASSONI RIBEIRO DESOTTI', valor: 89000,
              status: 'ATIVO', promotor: 'RENAN MARCONDES JOHAS', liner: 'KARINA FONTAN NASCIMENTO', closer: 'DANIEL MARCOS',
              entrada: 17799.88, efetiva: 8405 },
            { dt: '2026-06-19', contrato: 'COLLINA - 02/08', cliente: 'HELIO FERNANDES', valor: 81000, status: 'ATIVO',
              promotor: 'DANIELA MOURA', liner: 'PETERSON GUERREIRO', closer: 'JOSE NETO', entrada: 16200, efetiva: 540 },
            { dt: '2026-06-19', contrato: 'COLLINA - 05/47', cliente: 'HELIO FERNANDES', valor: 81000, status: 'ATIVO',
              promotor: 'DANIELA MOURA', liner: 'PETERSON GUERREIRO', closer: 'JOSE NETO', entrada: 16200, efetiva: 540 },
            { dt: '2026-06-20', contrato: 'COLLINA - 02/10', cliente: 'GABRIELE RAYA', valor: 98000, status: 'ATIVO',
              promotor: 'ANA CAROLINE', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS', entrada: 19600.08,
              efetiva: 1553.33 },
            { dt: '2026-06-20', contrato: 'COLLINA - 03/21', cliente: 'MARCOS VINICIUS HERRERA', valor: 90000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'THAMIRES FERNANDES MOREIRA', closer: 'RENAN FAGLIARI LOURENCO',
              entrada: 17999.96, efetiva: 5000 },
            { dt: '2026-06-20', contrato: 'COLLINA - 10/41', cliente: 'MARCOS VINICIUS HERRERA', valor: 90000,
              status: 'ATIVO', promotor: 'ANA CAROLINE', liner: 'THAMIRES FERNANDES MOREIRA', closer: 'RENAN FAGLIARI LOURENCO',
              entrada: 17999.96, efetiva: 5000 },
            { dt: '2026-06-20', contrato: 'COLLINA - 03/46', cliente: 'JEFERSON SOUSA FREITAS DOS SANTOS', valor: 81000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'JOSE NETO',
              entrada: 16200, efetiva: 675 },
            { dt: '2026-06-20', contrato: 'COLLINA - 13/26', cliente: 'JEFERSON SOUSA FREITAS DOS SANTOS', valor: 81000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'BRENDA KEROLAYNE OLIVEIRA DOS', closer: 'JOSE NETO',
              entrada: 16200, efetiva: 675 },
            { dt: '2026-06-20', contrato: 'COLLINA - 05/23', cliente: 'GUILHERME FERREIRA BIGATE', valor: 92100,
              status: 'ATIVO', promotor: 'PAULO VICTOR ORTIZ', liner: 'JANAINA SANCHES SANTANA', closer: 'JOSE NETO',
              entrada: 18420, efetiva: 614 },
            { dt: '2026-06-20', contrato: 'COLLINA - 10/48', cliente: 'ROGERIO APARECIDO SA RAMALHO', valor: 90000,
              status: 'ATIVO', promotor: 'MATHEUS ESLEY SILVA', liner: 'RENAN FAGLIARI LOURENCO', closer: 'JOSE NETO',
              entrada: 18000, efetiva: 1800 },
            { dt: '2026-06-21', contrato: 'COLLINA - 10/42', cliente: 'DOUGLAS NICORO', valor: 90000, status: 'ATIVO',
              promotor: 'JESSICA BARBOSA', liner: 'STELLA CHRISTY DIAS', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 18000 },
            { dt: '2026-06-21', contrato: 'COLLINA - 20/02', cliente: 'DOUGLAS NICORO', valor: 90000, status: 'ATIVO',
              promotor: 'JESSICA BARBOSA', liner: 'STELLA CHRISTY DIAS', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 18000, efetiva: 18000 },
            { dt: '2026-06-21', contrato: 'COLLINA - 20/08', cliente: 'MARX DE SENA RODRIGUES', valor: 90000, status: 'ATIVO',
              promotor: 'LARISSA RIBEIRO', liner: 'RENATA DORADO', closer: 'RENAN FAGLIARI LOURENCO', entrada: 18000,
              efetiva: 600 },
            { dt: '2026-06-21', contrato: 'COLLINA- 04/16', cliente: 'GUILHERME AUGUSTO ABRUNHOZA', valor: 79000,
              status: 'ATIVO', promotor: 'JESSICA BARBOSA', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 15800, efetiva: 526.88 },
            { dt: '2026-06-21', contrato: 'COLLINA - 05/28', cliente: 'GUILHERME AUGUSTO ABRUNHOZA', valor: 79000,
              status: 'ATIVO', promotor: 'JESSICA BARBOSA', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 15800, efetiva: 526.88 },
            { dt: '2026-06-21', contrato: 'COLLINA - 05/50', cliente: 'GUILHERME AUGUSTO ABRUNHOZA', valor: 79000,
              status: 'ATIVO', promotor: 'JESSICA BARBOSA', liner: 'STELLA CHRISTY DIAS', closer: 'DANIEL MARCOS',
              entrada: 15800.01, efetiva: 526.89 },
            { dt: '2026-06-21', contrato: 'COLLINA - 20/14', cliente: 'HENRIQUE MOREIRA MAGALHAES', valor: 90000,
              status: 'ATIVO', promotor: 'JONATAS FRANÇA DA SILVA', liner: 'JUNIOR PEREIRA', closer: 'JOSE NETO',
              entrada: 18000, efetiva: 1800 },
            { dt: '2026-06-21', contrato: 'COLLINA - 10/39', cliente: 'KAREN RAMOS FUKUDA SILVA', valor: 90000,
              status: 'ATIVO', promotor: 'PAULO VICTOR ORTIZ', liner: 'JUNIOR PEREIRA', closer: 'JOSE NETO',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-22', contrato: 'COLLINA - 32/40', cliente: 'GISELE SANTANA PEDREIRA', valor: 125000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 24999.91, efetiva: 3333.33 },
            { dt: '2026-06-22', contrato: 'COLLINA - 44/25', cliente: 'GISELE SANTANA PEDREIRA', valor: 125000,
              status: 'ATIVO', promotor: 'JOSYENE FREITAS', liner: 'RENATA DORADO', closer: 'LUIS ALVES DO AMARAL NETO',
              entrada: 24999.91, efetiva: 3333.33 },
            { dt: '2026-06-22', contrato: 'COLLINA - 02/51', cliente: 'VIVIANE ROBERTA DE SOUSA', valor: 80000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'STELLA CHRISTY DIAS', closer: 'BIANCA SANTOS',
              entrada: 15999.87, efetiva: 1662.06 },
            { dt: '2026-06-22', contrato: 'COLLINA - 02/25', cliente: 'EDUARDO TAVARES FERREIRA', valor: 80000,
              status: 'ATIVO', promotor: 'ANDRE CARRIÇO', liner: 'STELLA CHRISTY DIAS', closer: 'BIANCA SANTOS',
              entrada: 15999.87, efetiva: 1662.06 },
            { dt: '2026-06-22', contrato: 'COLLINA - 10/43', cliente: 'LETICIA GARCIA MATOS', valor: 90000, status: 'ATIVO',
              promotor: 'PAULO VICTOR ORTIZ', liner: 'RENAN FAGLIARI LOURENCO', closer: 'FABRICIO LELIS BIGNARDI',
              entrada: 18000, efetiva: 600 },
            { dt: '2026-06-22', contrato: 'COLLINA - 10/22', cliente: 'ANDERSON RODRIGUES SANTANA JUNIOR', valor: 90000,
              status: 'ATIVO', promotor: 'PEDRO HENRIQUE GOMES SANTOS', liner: 'JUNIOR PEREIRA', closer: 'RENATA BUENO',
              entrada: 18000, efetiva: 2000 },
            { dt: '2026-06-22', contrato: 'COLLINA - 10/47', cliente: 'VITORIA MACHADO PINTO', valor: 90990, status: 'ATIVO',
              promotor: 'MATHEUS ESLEY SILVA', liner: 'JUNIOR PEREIRA', closer: 'BIANCA SANTOS', entrada: 18197.96,
              efetiva: 988.88 },
            { dt: '2026-06-24', contrato: 'COLLINA - 05/36', cliente: 'OSVALDO EUSTAQUIO GOMES JUNIOR', valor: 80000,
              status: 'ATIVO', promotor: 'PEDRO HENRIQUE GOMES SANTOS', liner: 'RENATA DORADO', closer: 'FABRICIO LELIS BIGNARDI',
              entrada: 16000, efetiva: 4600 },
            { dt: '2026-06-25', contrato: 'COLLINA - 14/09', cliente: 'RODRIGO LUIS DOS SANTOS', valor: 76800,
              status: 'ATIVO', promotor: 'PEDRO HENRIQUE GOMES SANTOS', liner: 'JUNIOR PEREIRA', closer: 'DANIEL MARCOS',
              entrada: 15360, efetiva: 600 }
        ];

        let filteredData = [...rawData];
        let chartCloserInst, chartStatusInst, chartDailyInst, chartPromotorInst;

        const fmtBRL = (v) => 'R$ ' + Number(v).toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
        const fmtPct = (a, b) => b === 0 ? '0,00%' : ((a / b) * 100).toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 }) + '%';

        function getUniqueValues(key) {
            return [...new Set(rawData.map(r => r[key]).filter(Boolean))].sort();
        }

        function populateFilters() {
            const closes = getUniqueValues('closer');
            const liners = getUniqueValues('liner');
            const promotores = getUniqueValues('promotor');

            ['filterCloser', 'filterLiner', 'filterPromotor'].forEach(id => {
                document.getElementById(id).innerHTML = '<option value="">Todos</option>';
            });

            closes.forEach(v => {
                const o = document.createElement('option');
                o.value = v;
                o.textContent = v;
                document.getElementById('filterCloser').appendChild(o);
            });

            liners.forEach(v => {
                const o = document.createElement('option');
                o.value = v;
                o.textContent = v;
                document.getElementById('filterLiner').appendChild(o);
            });

            promotores.forEach(v => {
                const o = document.createElement('option');
                o.value = v;
                o.textContent = v;
                document.getElementById('filterPromotor').appendChild(o);
            });
        }

        function applyFilters() {
            const ds = document.getElementById('filterDateStart').value;
            const de = document.getElementById('filterDateEnd').value;
            const closer = document.getElementById('filterCloser').value;
            const liner = document.getElementById('filterLiner').value;
            const promotor = document.getElementById('filterPromotor').value;
            const status = document.getElementById('filterStatus').value;

            filteredData = rawData.filter(r => {
                if (ds && r.dt < ds) return false;
                if (de && r.dt > de) return false;
                if (closer && r.closer !== closer) return false;
                if (liner && r.liner !== liner) return false;
                if (promotor && r.promotor !== promotor) return false;
                if (status && r.status !== status) return false;
                return true;
            });

            updateAll();
        }

        function resetFilters() {
            document.getElementById('filterDateStart').value = '2026-06-01';
            document.getElementById('filterDateEnd').value = '2026-06-30';
            document.getElementById('filterCloser').value = '';
            document.getElementById('filterLiner').value = '';
            document.getElementById('filterPromotor').value = '';
            document.getElementById('filterStatus').value = '';
            filteredData = [...rawData];
            updateAll();
        }

        function updateKPIs() {
            const totalNegociado = filteredData.reduce((s, r) => s + r.valor, 0);
            const totalEntrada = filteredData.reduce((s, r) => s + r.entrada, 0);
            const totalEfetiva = filteredData.reduce((s, r) => s + r.efetiva, 0);
            const ativos = filteredData.filter(r => r.status === 'ATIVO').length;
            const cancelados = filteredData.filter(r => r.status === 'CANCELADO').length;

            document.getElementById('kpiRow').innerHTML = `
                <div class="kpi-card total">
                    <div class="kpi-label">💰 Valor Total Negociado</div>
                    <div class="kpi-value cyan">${fmtBRL(totalNegociado)}</div>
                    <div class="kpi-sub">${filteredData.length} contratos</div>
                </div>
                <div class="kpi-card entrada">
                    <div class="kpi-label">💳 Total da Entrada</div>
                    <div class="kpi-value green">${fmtBRL(totalEntrada)}</div>
                    <div class="kpi-sub">${fmtPct(totalEntrada, totalNegociado)} do negociado</div>
                </div>
                <div class="kpi-card percent">
                    <div class="kpi-label">✅ Entrada Efetiva</div>
                    <div class="kpi-value purple">${fmtBRL(totalEfetiva)}</div>
                    <div class="kpi-sub">${fmtPct(totalEfetiva, totalNegociado)} do negociado · ${fmtPct(totalEfetiva, totalEntrada)} da entrada</div>
                </div>
                <div class="kpi-card ativos">
                    <div class="kpi-label">🟢 Contratos Ativos</div>
                    <div class="kpi-value amber">${ativos}</div>
                    <div class="kpi-sub">${fmtPct(ativos, filteredData.length)} do total</div>
                </div>
                <div class="kpi-card cancelados">
                    <div class="kpi-label">🔴 Cancelados</div>
                    <div class="kpi-value pink">${cancelados}</div>
                    <div class="kpi-sub">${fmtPct(cancelados, filteredData.length)} do total</div>
                </div>
            `;
        }

        function updateCharts() {
            const closerMap = {};
            filteredData.forEach(r => { closerMap[r.closer] = (closerMap[r.closer] || 0) + r.efetiva; });
            const closerSorted = Object.entries(closerMap).sort((a, b) => b[1] - a[1]);

            const colors = [
                'rgba(180,77,255,0.8)', 'rgba(0,229,255,0.7)', 'rgba(0,230,118,0.7)',
                'rgba(255,179,0,0.7)', 'rgba(255,61,127,0.7)', 'rgba(100,140,255,0.7)',
                'rgba(0,200,200,0.7)', 'rgba(200,120,255,0.7)', 'rgba(255,150,50,0.7)'
            ];
            const borderColors = colors.map(c => c.replace('0.7', '1').replace('0.8', '1'));

            const ctx1 = document.getElementById('chartCloser').getContext('2d');
            if (chartCloserInst) chartCloserInst.destroy();

            chartCloserInst = new Chart(ctx1, {
                type: 'bar',
                data: {
                    labels: closerSorted.map(e => e[0].split(' ').slice(0, 2).join(' ')),
                    datasets: [{
                        label: 'Entrada Efetiva (R$)',
                        data: closerSorted.map(e => e[1]),
                        backgroundColor: closerSorted.map((_, i) => colors[i % colors.length]),
                        borderColor: closerSorted.map((_, i) => borderColors[i % borderColors.length]),
                        borderWidth: 1.5,
                        borderRadius: 8,
                        borderSkipped: false
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    aspectRatio: 2,
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            callbacks: { label: (c) => fmtBRL(c.raw) },
                            backgroundColor: 'rgba(10,14,28,0.95)',
                            titleColor: '#e8eaf6',
                            bodyColor: '#e8eaf6',
                            borderColor: 'rgba(100,120,255,0.4)',
                            borderWidth: 1
                        }
                    },
                    scales: {
                        x: { ticks: { color: '#9fa8da', font: { size: 10 }, maxRotation: 45 }, grid: { color: 'rgba(60,70,110,0.12)' } },
                        y: { ticks: { color: '#9fa8da', callback: (v) => 'R$ ' + (v / 1000).toFixed(0) + 'k', font: { size: 10 } }, grid: { color: 'rgba(60,70,110,0.12)' } }
                    }
                }
            });

            const ativosCount = filteredData.filter(r => r.status === 'ATIVO').length;
            const canceladosCount = filteredData.filter(r => r.status === 'CANCELADO').length;
            const ativosEfetiva = filteredData.filter(r => r.status === 'ATIVO').reduce((s, r) => s + r.efetiva, 0);
            const canceladosEfetiva = filteredData.filter(r => r.status === 'CANCELADO').reduce((s, r) => s + r.efetiva, 0);

            const ctx2 = document.getElementById('chartStatus').getContext('2d');
            if (chartStatusInst) chartStatusInst.destroy();

            chartStatusInst = new Chart(ctx2, {
                type: 'doughnut',
                data: {
                    labels: ['Ativos (' + ativosCount + ')', 'Cancelados (' + canceladosCount + ')'],
                    datasets: [{
                        data: [ativosEfetiva, canceladosEfetiva],
                        backgroundColor: ['rgba(0,230,118,0.75)', 'rgba(255,61,127,0.65)'],
                        borderColor: ['rgba(0,230,118,1)', 'rgba(255,61,127,1)'],
                        borderWidth: 2,
                        hoverBorderWidth: 3
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    plugins: {
                        legend: { position: 'bottom', labels: { color: '#e8eaf6', padding: 16, font: { size: 11 }, usePointStyle: true, pointStyleWidth: 10 } },
                        tooltip: {
                            callbacks: { label: (c) => fmtBRL(c.raw) + ' (' + fmtPct(c.raw, ativosEfetiva + canceladosEfetiva) + ')' },
                            backgroundColor: 'rgba(10,14,28,0.95)',
                            titleColor: '#e8eaf6',
                            bodyColor: '#e8eaf6',
                            borderColor: 'rgba(100,120,255,0.4)',
                            borderWidth: 1
                        }
                    }
                }
            });

            const dailyMap = {};
            filteredData.forEach(r => {
                const d = r.dt.slice(5);
                dailyMap[d] = (dailyMap[d] || 0) + r.efetiva;
            });
            const dailySorted = Object.entries(dailyMap).sort((a, b) => a[0].localeCompare(b[0]));

            const ctx3 = document.getElementById('chartDaily').getContext('2d');
            if (chartDailyInst) chartDailyInst.destroy();

            chartDailyInst = new Chart(ctx3, {
                type: 'line',
                data: {
                    labels: dailySorted.map(e => e[0]),
                    datasets: [{
                        label: 'Entrada Efetiva',
                        data: dailySorted.map(e => e[1]),
                        borderColor: '#00e5ff',
                        backgroundColor: 'rgba(0,229,255,0.08)',
                        borderWidth: 2.5,
                        fill: true,
                        tension: 0.4,
                        pointBackgroundColor: '#00e5ff',
                        pointBorderColor: '#050510',
                        pointBorderWidth: 2,
                        pointRadius: 5,
                        pointHoverRadius: 8
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    aspectRatio: 2,
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            callbacks: { label: (c) => fmtBRL(c.raw) },
                            backgroundColor: 'rgba(10,14,28,0.95)',
                            titleColor: '#e8eaf6',
                            bodyColor: '#e8eaf6',
                            borderColor: 'rgba(0,229,255,0.4)',
                            borderWidth: 1
                        }
                    },
                    scales: {
                        x: { ticks: { color: '#9fa8da', font: { size: 10 } }, grid: { color: 'rgba(60,70,110,0.12)' } },
                        y: { ticks: { color: '#9fa8da', callback: (v) => 'R$ ' + (v / 1000).toFixed(0) + 'k', font: { size: 10 } }, grid: { color: 'rgba(60,70,110,0.12)' } }
                    }
                }
            });

            const promotorMap = {};
            filteredData.forEach(r => { promotorMap[r.promotor] = (promotorMap[r.promotor] || 0) + r.efetiva; });
            const promotorSorted = Object.entries(promotorMap).sort((a, b) => b[1] - a[1]).slice(0, 10);

            const ctx4 = document.getElementById('chartPromotor').getContext('2d');
            if (chartPromotorInst) chartPromotorInst.destroy();

            chartPromotorInst = new Chart(ctx4, {
                type: 'bar',
                data: {
                    labels: promotorSorted.map(e => e[0].split(' ').slice(0, 2).join(' ')),
                    datasets: [{
                        label: 'Entrada Efetiva (R$)',
                        data: promotorSorted.map(e => e[1]),
                        backgroundColor: 'rgba(0,229,255,0.65)',
                        borderColor: 'rgba(0,229,255,1)',
                        borderWidth: 1.5,
                        borderRadius: 8,
                        borderSkipped: false
                    }]
                },
                options: {
                    indexAxis: 'y',
                    responsive: true,
                    maintainAspectRatio: true,
                    aspectRatio: 1.8,
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            callbacks: { label: (c) => fmtBRL(c.raw) },
                            backgroundColor: 'rgba(10,14,28,0.95)',
                            titleColor: '#e8eaf6',
                            bodyColor: '#e8eaf6',
                            borderColor: 'rgba(0,229,255,0.4)',
                            borderWidth: 1
                        }
                    },
                    scales: {
                        x: { ticks: { color: '#9fa8da', callback: (v) => 'R$ ' + (v / 1000).toFixed(0) + 'k', font: { size: 10 } }, grid: { color: 'rgba(60,70,110,0.12)' } },
                        y: { ticks: { color: '#9fa8da', font: { size: 10 } }, grid: { color: 'rgba(60,70,110,0.12)' } }
                    }
                }
            });
        }

        function updateTable() {
            const tbody = document.getElementById('tableBody');
            const sorted = [...filteredData].sort((a, b) => b.dt.localeCompare(a.dt) || b.efetiva - a.efetiva);
            document.getElementById('tableCount').textContent = '(' + sorted.length + ' registros)';

            if (sorted.length === 0) {
                tbody.innerHTML = '<tr><td colspan="11" class="no-data">Nenhum registro encontrado com os filtros atuais.</td></tr>';
                return;
            }

            tbody.innerHTML = sorted.map(r => `
                <tr>
                    <td>${r.dt.slice(5)}</td>
                    <td>${r.contrato}</td>
                    <td style="max-width:180px;overflow:hidden;text-overflow:ellipsis;" title="${r.cliente}">${r.cliente}</td>
                    <td>${fmtBRL(r.valor)}</td>
                    <td><span class="badge-status ${r.status === 'ATIVO' ? 'badge-ativo' : 'badge-cancelado'}">${r.status}</span></td>
                    <td>${r.promotor}</td>
                    <td>${r.liner}</td>
                    <td>${r.closer}</td>
                    <td>${fmtBRL(r.entrada)}</td>
                    <td style="font-weight:700;color:${r.efetiva > 0 ? '#00e676' : '#ff3d7f'}">${fmtBRL(r.efetiva)}</td>
                    <td>${fmtPct(r.efetiva, r.valor)}</td>
                </tr>
            `).join('');
        }

        function updateAll() {
            updateKPIs();
            updateCharts();
            updateTable();
        }

        ['filterDateStart', 'filterDateEnd', 'filterCloser', 'filterLiner', 'filterPromotor', 'filterStatus'].forEach(id => {
            document.getElementById(id).addEventListener('change', applyFilters);
        });

        populateFilters();
        updateAll();
    </script>
</body>
</html>
