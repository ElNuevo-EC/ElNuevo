
      <header className="text-center mb-12">
        <h1 className="text-4xl font-bold text-blue-400">SRI by El Neuvo</h1>
        <p className="mt-2 text-lg text-gray-300">
          Your Financial Superpower – Track Stocks, Crypto, ETFs, and More
        </p>
      </header>

      <section className="grid md:grid-cols-2 gap-10 mb-12">
        <Feature
          title="All-in-One Portfolio Tracking"
          desc="Sync with brokers, exchanges, and crypto wallets for full clarity."
        />
        <Feature
          title="Real-Time Market Data"
          desc="Get instant price updates on stocks, crypto, forex, gold, and more."
        />
        <Feature
          title="Smart Alerts & Insights"
          desc="Receive real-time alerts on price changes, trends, and movement."
        />
        <Feature
          title="Powerful Analytics"
          desc="Analyze gains, risks, allocations, and benchmark performance."
        />
      </section>

      <section className="bg-blue-950 p-6 rounded-2xl shadow-lg mb-12">
        <h2 className="text-2xl font-semibold text-blue-300 mb-4">
          Unlock Your Edge with Srigobec
        </h2>
        <ul className="list-disc list-inside space-y-2 text-gray-200">
          <li>Exclusive portfolio insights with deep dive analysis</li>
          <li>Live price updates – no need to refresh</li>
          <li>Unlimited account integrations</li>
          <li>“Why Is It Moving?” asset movement context</li>
          <li>Insider transaction alerts for public companies</li>
        </ul>
      </section>

      <footer className="text-center">
        <h3 className="text-xl font-medium mb-2">Invest Smarter with SRI</h3>
        <p className="text-gray-400 mb-4">
          Join thousands of investors tracking portfolios with confidence.
        </p>
        <Button className="bg-blue-600 hover:bg-blue-500 text-white px-6 py-2 rounded-full">
          📥 Download Now
        </Button>
      </footer>
    </div>
  );
}
function Feature({ title, desc }) {
  return (
    <div className="bg-gray-900 p-6 rounded-xl shadow-md">
      <h3 className="text-xl font-semibold text-blue-400 mb-2">{title}</h3>
      <p className="text-gray-300">{desc}</p>
    </div>
  );
}