![image](https://github.com/Triple-Estate/Sprint2/assets/107751548/cb438e4c-6cae-499f-a710-ac831e285f91)
![image](https://github.com/Triple-Estate/Sprint2/assets/107751548/e3a04bf3-2244-4ecb-89dd-0dd9c35d5e82)
![image](https://github.com/Triple-Estate/Sprint2/assets/107751548/4daf4b62-2966-4132-bccb-0461ce7905ce)

logoyu bu olarak güncelledim. indirip, 3e.png olarak ismini değiştirin ve wwwroot/imgs klasörü içine koyun.
![3e](https://github.com/Triple-Estate/Sprint2/assets/107751548/1a6aa452-df78-4421-ba82-b2999ae28340)

/* database güncellendi floor eklendi */
CREATE TABLE [dbo].[buy] (
    [Id]                INT            IDENTITY (1, 1) NOT NULL,
    [Description]       NVARCHAR (MAX) NOT NULL,
    [Price]             FLOAT (53)     NOT NULL,
    [YearBuilt]         NVARCHAR (MAX) NOT NULL,
    [SquareFeet]        NVARCHAR (MAX) NOT NULL,
    [Keywords]          NVARCHAR (MAX) NULL,
    [HomeType]          NVARCHAR (MAX) NOT NULL,
    [Room]              SMALLINT       NOT NULL,
    [Bath]              SMALLINT       NOT NULL,
    [Floor]             SMALLINT       NOT NULL,
    [Image]             NVARCHAR (MAX) NOT NULL,
    [IsSell]            BIT            NOT NULL,
    [HavePool]          BIT            NOT NULL,
    [HaveOnSiteParking] BIT            NOT NULL,
    [HavePark]          BIT            NOT NULL,
    CONSTRAINT [PK_buy] PRIMARY KEY CLUSTERED ([Id] ASC)
);

CREATE TABLE [dbo].[home] (
    [Id]                INT            IDENTITY (1, 1) NOT NULL,
    [Description]       NVARCHAR (MAX) NOT NULL,
    [Price]             FLOAT (53)     NOT NULL,
    [YearBuilt]         NVARCHAR (MAX) NOT NULL,
    [SquareFeet]        NVARCHAR (MAX) NOT NULL,
    [Keywords]          NVARCHAR (MAX) NULL,
    [HomeType]          NVARCHAR (MAX) NOT NULL,
    [Room]              SMALLINT       NOT NULL,
    [Bath]              SMALLINT       NOT NULL,
    [Image]             NVARCHAR (MAX) NOT NULL,
    [IsSell]            BIT            NOT NULL,
    [HavePool]          BIT            NOT NULL,
    [HaveOnSiteParking] BIT            NOT NULL,
    [HavePark]          BIT            NOT NULL,
    [Floor]             SMALLINT       NOT NULL,
    CONSTRAINT [PK_home] PRIMARY KEY CLUSTERED ([Id] ASC)[Uploading sprint2-UI.pdf…]()

);

PropertyList de "">" şeklinde anlamsız metin almaya başladım, lokasyonunu bulamadım dolayısıyla onu çözemedim. Bakabilirseniz sevinirim.
Filtering de any'i çözdüm. Location,room gibi diğerleri duruyor. Details kısmı da düzenlendi. Logolar düzenlendi.
