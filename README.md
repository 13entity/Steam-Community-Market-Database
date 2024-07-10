# SQL Database

    CREATE TABLE items
    (
        listing_id BIGINT PRIMARY KEY,
        asset_id BIGINT,
        link_id NUMERIC,
        timestamp INTEGER,
        item_name VARCHAR,
        price INTEGER,
        float NUMERIC(16, 15)
    );

    CREATE INDEX ON items(listing_id);