import React from "react";


<div className="w-40 bg-white border-l p-4 flex flex-col justify-center items-center">
<div className="text-xs text-gray-400">Quick Actions</div>
<div className="mt-3 space-y-3">
<button className="w-10 h-10 rounded-md bg-blue-50 grid place-items-center">⚡</button>
<button className="w-10 h-10 rounded-md bg-blue-50 grid place-items-center">⏳</button>
<button className="w-10 h-10 rounded-md bg-blue-50 grid place-items-center">🎮</button>
<button className="w-10 h-10 rounded-md bg-blue-50 grid place-items-center">⚙️</button>
</div>
</div>
</div>
</div>


{/* Right column (icons / abilities) */}
<aside className="col-span-1 space-y-6">
<div className="bg-white rounded-xl p-4 shadow text-center">
<div className="grid grid-cols-1 gap-4">
<IconCard title="King's Castling" />
<IconCard title="Pawn's Promotion" />
<IconCard title="Scholar's Mate" />
</div>
</div>


<div className="bg-white rounded-xl p-4 shadow">
<h4 className="text-sm font-semibold">More</h4>
<p className="text-xs text-gray-400 mt-2">Controls & quick toggles</p>
<div className="mt-4 space-y-3">
<ToggleBox label="Auto" />
<ToggleBox label="Boost" />
<ToggleBox label="Gamepad" />
</div>
</div>
</aside>
</div>
</div>
</div>
);
}


function IconCard({ title }) {
return (
<div className="bg-gradient-to-r from-sky-500 to-cyan-500 text-white rounded-lg p-3 flex items-center gap-3">
<div className="w-12 h-12 bg-white/20 rounded grid place-items-center">♟️</div>
<div className="text-left">
<div className="text-sm font-semibold">{title}</div>
<div className="text-xs opacity-80">description</div>
</div>
</div>
);
}


function ToggleBox({ label }) {
return (
<div className="flex items-center justify-between border rounded-md p-2">
<div className="text-sm">{label}</div>
<div className="w-8 h-4 bg-blue-50 rounded-full grid place-items-center text-xs">On</div>
</div>
);
}
