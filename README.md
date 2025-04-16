// components/Card.tsx
import QRCode from "qrcode.react";

export default function Card({ name, title, company, email, profileUrl }: any) {
  return (
    <div className="max-w-sm mx-auto mt-10 p-6 rounded-2xl shadow-lg bg-white text-center space-y-4">
      <h1 className="text-xl font-bold">{name}</h1>
      <p className="text-gray-600">{title} @ {company}</p>
      <p className="text-sm text-blue-600">{email}</p>
      <div className="mt-4">
        <QRCode value={profileUrl} size={128} />
        <p className="text-xs mt-2 text-gray-500">QRコードで名刺を共有</p>
      </div>
    </div>
  );
}# -
