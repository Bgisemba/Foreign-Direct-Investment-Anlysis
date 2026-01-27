# Foreign-Direct-Investment-Anlysis
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global FDI Analytics | Premium Dashboard</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
    <div class="glass-bg"></div>
    <div class="dashboard-container">
        <!-- Sidebar -->
        <aside class="sidebar">
            <div class="logo-section">
                <div class="logo-icon"></div>
                <h1>FDI Analytics</h1>
            </div>
            <nav>
                <a href="#" class="nav-item active" id="nav-overview">Overview</a>
                <a href="#" class="nav-item" id="nav-sectors">Sectors</a>
                <a href="#" class="nav-item" id="nav-regions">Regions</a>
                <a href="#" class="nav-item" id="nav-reports">Reports</a>
            </nav>
            <div class="sidebar-footer">
                <p>Global Insights v2.0</p>
            </div>
        </aside>

        <!-- Main Content -->
        <main class="main-content">
            <header>
                <div class="header-info">
                    <h2>Global Investment Overview</h2>
                    <p>Real-time Foreign Direct Investment tracking & analytics</p>
                </div>
                <div class="user-profile">
                    <div class="search-bar">
                        <input type="text" placeholder="Search analytics...">
                    </div>
                    <div class="avatar">AN</div>
                </div>
            </header>

            <!-- Stats Grid -->
            <section class="stats-grid">
                <div class="stat-card" id="card-total-fdi">
                    <span class="label">Total FDI Inflow</span>
                    <h3>$3.42T</h3>
                    <div class="trend up">+12.4% <span class="period">vs LY</span></div>
                </div>
                <div class="stat-card" id="card-avg-growth">
                    <span class="label">Avg. Growth Rate</span>
                    <h3>8.7%</h3>
                    <div class="trend up">+1.2% <span class="period">vs LY</span></div>
                </div>
                <div class="stat-card" id="card-investor-cnt">
                    <span class="label">Active Investors</span>
                    <h3>1,248</h3>
                    <div class="trend down">-2.1% <span class="period">vs LY</span></div>
                </div>
                <div class="stat-card" id="card-market-stab">
                    <span class="label">Market Stability</span>
                    <h3>High</h3>
                    <div class="status-indicator"></div>
                </div>
            </section>

            <!-- Charts Section -->
            <section class="charts-section">
                <div class="chart-container large">
                    <div class="chart-header">
                        <h3>Investment Trends (2020 - 2025)</h3>
                    </div>
                    <canvas id="mainTrendChart"></canvas>
                </div>
                <div class="charts-sub-grid">
                    <div class="chart-container">
                        <div class="chart-header">
                            <h3>Sector Distribution</h3>
                        </div>
                        <canvas id="sectorPieChart"></canvas>
                    </div>
                    <div class="chart-container">
                        <div class="chart-header">
                            <h3>Top Regional Inflows</h3>
                        </div>
                        <canvas id="regionalBarChart"></canvas>
                    </div>
                </div>
            </section>
        </main>
    </div>
    <script src="script.js"></script>
</body>
</html>
