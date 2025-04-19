Fix	Why it helped
node node_modules/vite/bin/vite.js build	Avoided Linux permission issues with vite binary
.npmrc with unsafe-perm=true	Ensured smooth dependency installation
Cleaned node_modules + package-lock.json	Removed corrupted or incompatible modules
Correct Vercel root & build settings	Made sure Vercel knows exactly what to build
