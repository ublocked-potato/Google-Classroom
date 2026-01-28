<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>potatozone - Project Notes</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; overflow-x: hidden; margin: 0; }
        .glass { background: rgba(20, 20, 25, 0.9); backdrop-filter: blur(20px); border-bottom: 1px solid rgba(128, 108, 161, 0.3); }
        .game-card { transition: all 0.4s cubic-bezier(0.23, 1, 0.32, 1); cursor: pointer; }
        .game-card:hover { transform: translateY(-8px); filter: brightness(1.1); }
        .hidden-cloak { display: none !important; }
        .doc-canvas { background: #1a1a1f; box-shadow: 0 0 30px rgba(128, 108, 161, 0.2); min-height: 1056px; width: 816px; margin: 30px auto; padding: 90px; text-align: left; color: #e2e8f0; }
        #game-overlay { background: #000; }
        ::-webkit-scrollbar { width: 5px; }
        ::-webkit-scrollbar-thumb { background: rgba(128, 108, 161, 0.5); border-radius: 10px; }
        ::-webkit-scrollbar-track { background: rgba(15, 15, 20, 0.5); }
    </style>
</head>
<body class="bg-black">

    <div id="cloak-layer" class="hidden-cloak fixed inset-0 bg-[#1a1a1f] z-[9999] overflow-y-auto">
        <nav class="bg-[#141419]/95 backdrop-blur-md border-b border-[#806CA1]/30 p-2 flex items-center justify-between sticky top-0">
            <div class="flex items-center gap-4 px-4">
                <div class="w-7 h-9 bg-[#806CA1] rounded-sm"></div>
                <div>
                    <h1 class="text-md font-medium text-gray-200">Research_Paper_Final_v2</h1>
                    <div class="flex gap-3 text-[11px] text-gray-400 font-normal">
                        <span>File</span><span>Edit</span><span>View</span><span>Insert</span><span>Format</span><span>Tools</span>
                    </div>
                </div>
            </div>
            <div class="flex gap-4 px-6 items-center">
                <span class="text-[11px] text-gray-500 italic">All changes saved to Drive</span>
                <div class="w-7 h-7 rounded-full bg-[#806CA1] text-white flex items-center justify-center text-[10px]">A</div>
            </div>
        </nav>
        <div class="doc-canvas">
            <h2 class="text-3xl mb-8 font-serif text-gray-100">Analysis of Macroeconomic Trends</h2>
            <p class="text-gray-200 leading-7 mb-6 font-serif">
                The fundamental principles of market equilibrium rely heavily on the interaction between supply and demand.
                In this section, we explore how external shocks to the supply chain can lead to inflationary pressure within developing economies...
            </p>
            <p class="text-gray-200 leading-7 font-serif">
                Data suggests that the fiscal policies implemented in the early 2020s provided a temporary buffer, though
                the long-term sustainability of such debt-to-GDP ratios remains a point of contention among leading economists.
            </p>
        </div>
    </div>

    <div id="app-wrapper">
        <header class="glass sticky top-0 z-50 px-8 py-4 flex flex-col md:flex-row items-center justify-between gap-6">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-[#806CA1] rounded-xl flex items-center justify-center text-white shadow-2xl shadow-[#806CA1]/25">
                    <span class="font-black text-xl">PZ</span>
                </div>
                <span class="text-2xl font-bold tracking-tighter font-['Montserrat'] text-white">
                    potato<span class="text-[#806CA1]">zone</span>
                </span>
            </div>

            <div class="flex-1 max-w-xl w-full flex items-center gap-3 bg-[#1a1a1f]/80 rounded-full px-5 py-2 shadow-xl border border-[#806CA1]/20">
                <svg class="text-gray-400" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <circle cx="11" cy="11" r="8"></circle>
                    <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                </svg>
                <input type="text" id="game-search" placeholder="Search the library..." class="bg-transparent w-full focus:outline-none text-sm font-medium text-gray-200 placeholder-gray-400">
                <select id="game-sort" class="bg-transparent border-none text-xs font-bold text-[#806CA1] uppercase focus:ring-0 cursor-pointer">
                    <option value="pop">Popular</option>
                    <option value="az">A-Z</option>
                </select>
            </div>

            <div class="flex gap-2">
                <button onclick="exportData()" class="px-4 py-2 bg-[#1a1a1f]/80 text-xs font-bold rounded-lg border border-[#806CA1]/30 text-gray-200 hover:bg-[#806CA1]/10 transition backdrop-blur-sm">EXPORT</button>
                <button onclick="document.getElementById('import-file').click()" class="px-4 py-2 bg-[#1a1a1f]/80 text-xs font-bold rounded-lg border border-[#806CA1]/30 text-gray-200 hover:bg-[#806CA1]/10 transition backdrop-blur-sm">IMPORT</button>
                <input type="file" id="import-file" class="hidden" onchange="importData(event)">
            </div>
        </header>

        <main class="max-w-7xl mx-auto p-10">
            <div id="grid-container" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 xl:grid-cols-6 gap-8">
                <div class="col-span-full text-center py-20 animate-pulse text-gray-500 font-medium">Syncing with GitHub Assets...</div>
            </div>
        </main>
    </div>

    <div id="game-overlay" class="fixed inset-0 hidden-cloak z-[100] flex flex-col">
        <div class="p-3 bg-[#141419]/95 backdrop-blur-md flex justify-between items-center px-8 border-b border-[#806CA1]/30">
            <div id="game-title" class="font-bold text-white font-['Montserrat'] truncate"></div>
            <div class="flex gap-3">
                <button onclick="stealthLaunch()" class="text-[10px] font-black uppercase tracking-widest px-4 py-2 bg-gray-900/50 rounded-md hover:bg-gray-800 backdrop-blur-sm border border-gray-600">Stealth Tab</button>
                <button onclick="exitGame()" class="text-[10px] font-black uppercase tracking-widest px-4 py-2 bg-red-600 text-white rounded-md hover:bg-red-700">Close Game</button>
            </div>
        </div>
        <div id="game-frame-host" class="flex-1 w-full bg-black relative"></div>
    </div>

    <script>
        const API = {
            zones: "https://cdn.jsdelivr.net/gh/gn-math/assets@main/zones.json",
            covers: "https://cdn.jsdelivr.net/gh/gn-math/covers@main",
            html:   "https://cdn.jsdelivr.net/gh/gn-math/html@main",
            stats:  "https://data.jsdelivr.net/v1/stats/packages/gh/gn-math/html@main/files?period=year",
            commits:"https://api.github.com/repos/gn-math/assets/commits"
        };

        let games_data = [];
        let popularity_data = {};
        let active_html = "";

        async function boot() {
            let version = "";
            try {
                const commitFetch = await fetch(API.commits);
                if (commitFetch.ok) {
                    const commits = await commitFetch.json();
                    if (Array.isArray(commits) && commits[0]?.sha) {
                        version = `?v=${commits[0].sha}`;
                    }
                }
            } catch(e) {
                console.log("GitHub API Limited - Using standard CDN");
            }

            try {
                const [dbRes, statsRes] = await Promise.allSettled([
                    fetch(API.zones + version).then(r => r.json()),
                    fetch(API.stats).then(r => r.json())
                ]);

                if (statsRes.status === "fulfilled" && statsRes.value.files) {
                    statsRes.value.files.forEach(f => {
                        const cleanId = f.name.split('.')[0];
                        popularity_data[cleanId] = f.total;
                    });
                }

                if (dbRes.status === "fulfilled" && Array.isArray(dbRes.value)) {
                    games_data = dbRes.value
                        .filter(item => item.id && item.url && item.url.includes("{HTML_URL}"))
                        .map(item => {
                            const cleanId = (item.id + "").replace(".html", "");
                            let finalUrl = item.url
                                .replace("{HTML_URL}", API.html)
                                .replace("{COVER_URL}", API.covers);
                            if (!finalUrl.endsWith(".html") && !finalUrl.startsWith("http")) {
                                finalUrl += ".html";
                            }
                            const processed_cover = (item.cover || "")
                                .replace("{COVER_URL}", API.covers)
                                .replace("{HTML_URL}", API.html);
                            return {
                                ...item,
                                id: cleanId,
                                processed_url: finalUrl,
                                processed_cover,
                                hits: popularity_data[cleanId] || 0
                            };
                        });
                }
                renderGrid();
            } catch(e) {
                document.getElementById('grid-container').innerHTML =
                    `<div class="col-span-full text-center py-20 text-gray-500">Failed to connect to asset server.</div>`;
            }
        }

        function renderGrid() {
            const grid = document.getElementById('grid-container');
            const search = document.getElementById('game-search').value.toLowerCase();
            const sort = document.getElementById('game-sort').value;

            let filtered = games_data.filter(g => (g.name || "").toLowerCase().includes(search));
            if (sort === 'pop') filtered.sort((a, b) => b.hits - a.hits);
            if (sort === 'az')  filtered.sort((a, b) => (a.name || "").localeCompare(b.name || ""));

            if (!filtered.length) {
                grid.innerHTML = `<div class="col-span-full text-center py-20 text-gray-500 font-medium">No games found.</div>`;
                return;
            }

            grid.innerHTML = filtered.map(game => `
                <div class="game-card group" onclick="loadGame('${game.id}')">
                    <div class="aspect-[4/5] overflow-hidden rounded-2xl bg-[#1a1a1f] relative shadow-2xl shadow-black/50 border border-[#806CA1]/20">
                        <img src="${game.processed_cover}" class="w-full h-full object-cover grayscale-[0.3] group-hover:grayscale-0 transition-all duration-500" loading="lazy">
                        <div class="absolute inset-0 bg-[#806CA1]/20 opacity-0 group-hover:opacity-100 transition-opacity backdrop-blur-sm"></div>
                    </div>
                    <div class="mt-4">
                        <p class="text-xs font-black text-[#806CA1] uppercase tracking-widest mb-1">
                            ${game.hits > 5000 ? 'Hot' : 'Premium'}
                        </p>
                        <p class="text-sm font-bold text-white truncate">${game.name}</p>
                    </div>
                </div>
            `).join('');
        }

        async function loadGame(id) {
            const game = games_data.find(g => g.id === id);
            if (!game) return;

            document.getElementById('game-title').innerText = game.name;
            const overlay = document.getElementById('game-overlay');
            overlay.classList.remove('hidden-cloak');

            try {
                const res = await fetch(game.processed_url);
                if (!res.ok) throw new Error("404");
                let html = await res.text();

                const injection = `
                    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
                    <style>
                        * { font-family: 'Montserrat', sans-serif !important; }
                        body, html { margin: 0; padding: 0; width: 100vw; height: 100vh; overflow: hidden; background: #000; }
                        iframe, canvas { width: 100% !important; height: 100% !important; }
                    </style>
                `;
                active_html = html.includes('<head>')
                    ? html.replace('<head>', `<head>${injection}`)
                    : injection + html;

                const host = document.getElementById('game-frame-host');
                host.innerHTML = `<iframe id="game-src" class="w-full h-full border-none"></iframe>`;
                const frame = document.getElementById('game-src');
                const doc = frame.contentWindow.document;
                doc.open();
                doc.write(active_html);
                doc.close();
            } catch(e) {
                alert("Game file not found on GitHub. (404)");
                exitGame();
            }
        }

        function exitGame() {
            document.getElementById('game-overlay').classList.add('hidden-cloak');
            document.getElementById('game-frame-host').innerHTML = '';
        }

        function stealthLaunch() {
            if (!active_html) return;
            const win = window.open('about:blank', '_blank');
            if (!win) return;
            win.document.open();
            win.document.write(active_html);
            win.document.close();
        }

        function exportData() {
            const data = { storage: {...localStorage}, timestamp: Date.now() };
            const blob = new Blob([JSON.stringify(data)], {type: 'application/json'});
            const a = document.createElement('a');
            a.href = URL.createObjectURL(blob);
            a.download = `potatozone-data-${Date.now()}.json`;
            a.click();
        }

        function importData(e) {
            const reader = new FileReader();
            reader.onload = (event) => {
                const data = JSON.parse(event.target.result);
                Object.entries(data.storage || {}).forEach(([k, v]) => localStorage.setItem(k, v));
                alert("Data synced. Refreshing...");
                location.reload();
            };
            reader.readAsText(e.target.files[0]);
        }

        window.onkeydown = (e) => {
            if (e.key === 'Escape' || e.key === '`') {
                const cloak = document.getElementById('cloak-layer');
                cloak.classList.toggle('hidden-cloak');
                document.title = cloak.classList.contains('hidden-cloak')
                    ? "potatozone"
                    : "Google Docs - Project Notes";
            }
        };

        document.getElementById('game-search').addEventListener('input', renderGrid);
        document.getElementById('game-sort').addEventListener('change', renderGrid);

        boot();
    </script>
</body>
</html>
