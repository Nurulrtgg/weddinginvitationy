import React, { useState } from "react";

export const InstagramStory = (): JSX.Element => {
  const [isInvitationOpened, setIsInvitationOpened] = useState(false);

  const invitationData = {
    title: "The Wedding Of",
    greeting: "Kepada Yth. Bapak/Ibu/Saudara/i:",
    recipient: "Nurul dan Partner Di Tempat",
    buttonText: "Open Invitation",
  };

  const handleOpenInvitation = () => {
    setIsInvitationOpened(true);
  };

  return (
    <main className="bg-white grid justify-items-center [align-items:start] w-screen min-h-screen">
      <article className="bg-white w-[1092px] h-[1941.33px] relative">
        <section className="relative h-[1936px] top-[3px] bg-[url(/tak-berjudul147-20250807145957-1.png)] bg-[100%_100%] bg-no-repeat">
          <header className="absolute w-[489px] h-[79px] top-[567px] left-[338px]">
            <h1 className="[font-family:'Recoleta-RegularDEMO',Helvetica] font-normal text-black text-[64.8px] tracking-[0] leading-[100.5px] whitespace-nowrap">
              {invitationData.title}
            </h1>
          </header>

          <div className="absolute w-[308px] top-[1217px] left-[429px]">
            <p className="h-[39px] [font-family:'Recoleta-RegularDEMO',Helvetica] font-normal text-black text-[20.7px] tracking-[0] leading-[32.1px]">
              {invitationData.greeting}
            </p>

            <p className="h-[39px] mt-[0px] ml-[29px] [font-family:'Recoleta-RegularDEMO',Helvetica] font-normal text-black text-[20.7px] tracking-[0] leading-[32.1px]">
              {invitationData.recipient}
            </p>
          </div>

          <div className="absolute w-[271px] h-10 top-[1338px] left-[449px] rounded-[15.15px]">
            <button
              className="absolute w-[271px] h-10 top-0 left-0 bg-[#fefefc] rounded-[15.15px] cursor-pointer transition-all duration-200 hover:bg-[#f5f5f3] focus:outline-none focus:ring-2 focus:ring-black focus:ring-opacity-50 active:scale-95"
              onClick={handleOpenInvitation}
              aria-label="Open wedding invitation"
              type="button"
            >
              <span className="absolute w-[156px] h-[39px] top-0 left-[62px] [font-family:'Recoleta-RegularDEMO',Helvetica] font-normal text-black text-[20.7px] tracking-[0] leading-[32.1px] pointer-events-none">
                {invitationData.buttonText}
              </span>
            </button>
          </div>
        </section>
      </article>
    </main>
  );
};
