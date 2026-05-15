<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HOA Board of Directors</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: Georgia, 'Times New Roman', serif; background: #f9f8f6; color: #1a1a1a; }
  .wrap { max-width: 860px; margin: 0 auto; padding: 2rem 1rem; }
  .header { text-align: center; margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #e0ddd8; }
  .header-eyebrow { font-family: Arial, sans-serif; font-size: 11px; letter-spacing: 0.14em; text-transform: uppercase; color: #999; margin-bottom: 6px; }
  .header-title { font-size: 26px; font-weight: normal; color: #1a1a1a; }
  .header-sub { font-family: Arial, sans-serif; font-size: 13px; color: #888; margin-top: 5px; }
  .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 14px; }
  .card { background: #fff; border: 1px solid #e0ddd8; border-radius: 10px; padding: 1.2rem; cursor: pointer; transition: border-color 0.15s, box-shadow 0.15s; }
  .card:hover { border-color: #b0aaa0; box-shadow: 0 2px 8px rgba(0,0,0,0.07); }
  .card.active { border: 2px solid #4a7fa5; }
  .card-top { display: flex; align-items: center; gap: 13px; margin-bottom: 12px; }
  .avatar { width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-family: Arial, sans-serif; font-size: 14px; font-weight: bold; flex-shrink: 0; }
  .av-blue   { background: #ddeaf5; color: #1a4f78; }
  .av-teal   { background: #d4eee4; color: #0b4e36; }
  .av-amber  { background: #faebd4; color: #6b3c0a; }
  .av-coral  { background: #fae5df; color: #5a1e0e; }
  .av-purple { background: #eceaf9; color: #2e2468; }
  .av-green  { background: #e4f0d8; color: #1e3d09; }
  .name { font-size: 15px; font-weight: bold; color: #1a1a1a; font-family: Georgia, serif; }
  .role-badge { display: inline-block; font-family: Arial, sans-serif; font-size: 11px; padding: 3px 9px; border-radius: 5px; margin-top: 4px; }
  .badge-blue   { background: #ddeaf5; color: #1a4f78; }
  .badge-teal   { background: #d4eee4; color: #0b4e36; }
  .badge-amber  { background: #faebd4; color: #6b3c0a; }
  .badge-coral  { background: #fae5df; color: #5a1e0e; }
  .badge-purple { background: #eceaf9; color: #2e2468; }
  .badge-green  { background: #e4f0d8; color: #1e3d09; }
  .divider { border: none; border-top: 1px solid #f0ede8; margin: 10px 0; }
  .bio { font-family: Arial, sans-serif; font-size: 13px; color: #555; line-height: 1.6; }
  .meta-row { display: flex; gap: 14px; margin-top: 10px; flex-wrap: wrap; }
  .meta-item { display: flex; align-items: center; gap: 5px; font-family: Arial, sans-serif; font-size: 11px; color: #999; }
  .meta-icon { font-size: 13px; }
  .detail-panel { background: #f2f0ec; border: 1px solid #e0ddd8; border-radius: 10px; padding: 1.5rem; margin-top: 14px; display: none; }
  .detail-panel.visible { display: block; }
  .detail-header { display: flex; align-items: center; gap: 16px; margin-bottom: 1.2rem; }
  .detail-avatar { width: 62px; height: 62px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-family: Arial, sans-serif; font-size: 17px; font-weight: bold; flex-shrink: 0; }
  .detail-name { font-size: 18px; font-weight: normal; color: #1a1a1a; font-family: Georgia, serif; }
  .detail-role { font-family: Arial, sans-serif; font-size: 13px; color: #666; margin-top: 3px; }
  .detail-since { font-family: Arial, sans-serif; font-size: 12px; color: #999; margin-top: 2px; }
  .section-label { font-family: Arial, sans-serif; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: #aaa; margin: 1rem 0 5px; }
  .detail-bio { font-family: Arial, sans-serif; font-size: 13px; color: #555; line-height: 1.75; }
  .initiatives { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 5px; }
  .init-tag { font-family: Arial, sans-serif; font-size: 12px; padding: 3px 10px; background: #fff; border: 1px solid #d8d4ce; border-radius: 5px; color: #666; }
  .contact-row { display: flex; align-items: center; gap: 8px; font-family: Arial, sans-serif; font-size: 13px; color: #555; margin-top: 7px; }
  .close-btn { float: right; background: #fff; border: 1px solid #d8d4ce; border-radius: 6px; padding: 4px 12px; font-family: Arial, sans-serif; font-size: 12px; color: #666; cursor: pointer; }
  .close-btn:hover { background: #f5f3ef; }
</style>
</head>
<body>
<div class="wrap">
  <div class="header">
    <div class="header-eyebrow">Maplewood Estates</div>
    <div class="header-title">Board of Directors</div>
    <div class="header-sub">2024–2025 Term &middot; 6 Members</div>
  </div>
  <div class="grid" id="grid"></div>
  <div class="detail-panel" id="detail"></div>
</div>
<script>
const members = [
  {
    initials: "LH", av: "av-blue", badge: "badge-blue",
    name: "Linda Hargrove", role: "President", years: "3 years on board",
    bio: "Retired school principal with a passion for community governance. Led the 2023 neighborhood beautification drive.",
    initiatives: ["Street lighting upgrade", "Welcome committee", "Annual picnic"],
    email: "l.hargrove@maplewoodhoa.org", phone: "(555) 204-8810",
    full_bio: "Linda joined the board after retiring from 28 years as a public school principal. She brings a collaborative leadership style and has championed initiatives to improve common areas and increase homeowner participation. Under her leadership, board meeting attendance has grown by 40%.",
    since: "Board member since 2021"
  },
  {
    initials: "MR", av: "av-teal", badge: "badge-teal",
    name: "Marcus Reyes", role: "Vice President", years: "2 years on board",
    bio: "Civil engineer by trade. Oversees infrastructure maintenance and contractor relations for the community.",
    initiatives: ["Pool renovation", "Sidewalk repair", "Storm drain audit"],
    email: "m.reyes@maplewoodhoa.org", phone: "(555) 317-4420",
    full_bio: "Marcus is a licensed civil engineer with 18 years of experience in municipal infrastructure. He serves as the board's technical lead, reviewing contractor bids and ensuring all physical improvements meet code. He personally supervised the 2023 pool renovation that came in 12% under budget.",
    since: "Board member since 2022"
  },
  {
    initials: "DA", av: "av-amber", badge: "badge-amber",
    name: "Diane Ashworth", role: "Treasurer", years: "5 years on board",
    bio: "CPA and former bank manager who oversees HOA finances, reserve funds, and annual budget planning.",
    initiatives: ["Reserve fund growth", "Dues transparency report", "Online payment portal"],
    email: "d.ashworth@maplewoodhoa.org", phone: "(555) 482-6631",
    full_bio: "Diane has managed the HOA's finances since 2019, growing the reserve fund from $48K to over $210K. She introduced the annual budget transparency report and pushed for the online dues payment portal, which increased on-time payments by 28%.",
    since: "Board member since 2019"
  },
  {
    initials: "TN", av: "av-coral", badge: "badge-coral",
    name: "Tom Nguyen", role: "Secretary", years: "1 year on board",
    bio: "Paralegal and notary public. Maintains meeting minutes, official records, and HOA governing documents.",
    initiatives: ["Digital records archive", "Bylaw review 2024", "Homeowner FAQ portal"],
    email: "t.nguyen@maplewoodhoa.org", phone: "(555) 594-0027",
    full_bio: "Tom joined the board in 2023 after years of volunteering at neighborhood events. His legal background has been invaluable in digitizing governing documents and conducting a thorough review of the community bylaws. He is the primary contact for deed restriction questions.",
    since: "Board member since 2023"
  },
  {
    initials: "PW", av: "av-purple", badge: "badge-purple",
    name: "Patricia Wolfe", role: "At-Large Member", years: "4 years on board",
    bio: "Landscape architect who chairs the Architectural Review Committee and manages vendor relationships.",
    initiatives: ["Tree canopy project", "ARC process redesign", "Native plant guide"],
    email: "p.wolfe@maplewoodhoa.org", phone: "(555) 703-1198",
    full_bio: "Patricia is a licensed landscape architect who redesigned the ARC approval process, cutting review time from 6 weeks to 10 days. She led the community tree canopy project that planted 38 new trees along common area pathways and produced a free native plant guide distributed to all 214 homes.",
    since: "Board member since 2020"
  },
  {
    initials: "JK", av: "av-green", badge: "badge-green",
    name: "James Kim", role: "At-Large Member", years: "1 year on board",
    bio: "Software product manager focused on digital tools, community communications, and resident engagement.",
    initiatives: ["HOA app rollout", "Newsletter redesign", "Online voting system"],
    email: "j.kim@maplewoodhoa.org", phone: "(555) 811-5543",
    full_bio: "James joined the board to modernize how the HOA communicates with residents. He led the launch of the community mobile app, which now has 160 active users, and introduced online voting for the first time in the HOA's history. He is also the editor of the monthly digital newsletter.",
    since: "Board member since 2023"
  }
];

let activeId = null;

function render() {
  document.getElementById('grid').innerHTML = members.map((m, i) => `
    <div class="card${activeId === i ? ' active' : ''}" onclick="select(${i})">
      <div class="card-top">
        <div class="avatar ${m.av}">${m.initials}</div>
        <div>
          <div class="name">${m.name}</div>
          <span class="role-badge ${m.badge}">${m.role}</span>
        </div>
      </div>
      <hr class="divider">
      <div class="bio">${m.bio}</div>
      <div class="meta-row">
        <div class="meta-item"><span class="meta-icon">&#128197;</span>${m.years}</div>
        <div class="meta-item"><span class="meta-icon">&#9993;</span>${m.email}</div>
      </div>
    </div>
  `).join('');
}

function select(i) {
  const panel = document.getElementById('detail');
  if (activeId === i) {
    activeId = null;
    panel.classList.remove('visible');
    panel.innerHTML = '';
  } else {
    activeId = i;
    const m = members[i];
    panel.innerHTML = `
      <button class="close-btn" onclick="closePanel()">&#10005; Close</button>
      <div class="detail-header">
        <div class="detail-avatar ${m.av}">${m.initials}</div>
        <div>
          <div class="detail-name">${m.name}</div>
          <div class="detail-role">${m.role}</div>
          <div class="detail-since">${m.since}</div>
        </div>
      </div>
      <hr class="divider">
      <div class="section-label">About</div>
      <div class="detail-bio">${m.full_bio}</div>
      <div class="section-label">Current initiatives</div>
      <div class="initiatives">${m.initiatives.map(t => `<span class="init-tag">${t}</span>`).join('')}</div>
      <div class="section-label">Contact</div>
      <div class="contact-row"><span>&#9993;</span> ${m.email}</div>
      <div class="contact-row"><span>&#128222;</span> ${m.phone}</div>
    `;
    panel.classList.add('visible');
    panel.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
  }
  render();
}

function closePanel() {
  activeId = null;
  document.getElementById('detail').classList.remove('visible');
  document.getElementById('detail').innerHTML = '';
  render();
}

render();
</script>
</body>
</html>
