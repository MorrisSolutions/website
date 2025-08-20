export default function Home() {
return (
<div className="min-h-screen bg-white text-gray-900 p-6">
<header className="text-center py-10">
<img src="/morris-solutions-logo.png" alt="Morris Solutions Logo" width={120} height={120} className="mx-auto mb-4" />
<h1 className="text-4xl font-bold text-blue-600">Morris Solutions</h1>
<p className="text-lg mt-2">Tech-Savvy Analytics for Smarter Decisions</p>
</header>


<section className="max-w-4xl mx-auto grid gap-10 md:grid-cols-2 sm:grid-cols-1">
<div>
<h2 className="text-2xl font-semibold text-blue-500 mb-2">About Us</h2>
<p>
Morris Solutions empowers small businesses and nonprofits with customized data dashboards, KPI tracking,
and strategic insights. Our electric-blue branding and tech-forward approach make data easy to understand
and act on.
</p>
</div>


<div>
<h2 className="text-2xl font-semibold text-blue-500 mb-2">Our Services</h2>
<ul className="list-disc pl-5">
<li>Custom Data Dashboards (Power BI, Excel, Tableau)</li>
<li>KPI Monitoring & Performance Reporting</li>
<li>Forecasting & Predictive Analytics</li>
<li>Workshops & Training on Data Literacy</li>
</ul>
</div>


<div>
<h2 className="text-2xl font-semibold text-blue-500 mb-2">Why Choose Us</h2>
<p>
With a unique blend of IT support, nonprofit experience, and analytics expertise, we tailor our services
to fit your goals—not the other way around. Clear visuals, actionable insights, and consistent delivery.
</p>
</div>


<div>
<h2 className="text-2xl font-semibold text-blue-500 mb-2">Contact</h2>
<address className="not-italic">
<p>Email: <a href="mailto:info@morrissolutions.com" className="text-blue-600">info@morrissolutions.com</a></p>
<p>Phone: <a href="tel:+12136591754" className="text-blue-600">(213) 659-1754</a></p>
<p>Location: East Point, GA</p>
</address>
</div>
</section>


<footer className="text-center mt-12 text-sm text-gray-500">
&copy; {new Date().getFullYear()} Morris Solutions. All rights reserved.
</footer>
</div>
);
}
