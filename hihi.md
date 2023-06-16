```mermaid
flowchart TD

admin[admin]
pAdmin[partner admin]

subgraph BANKPOS
  subgraph Admin
		admin
      subgraph PartnerAdmin
        pAdmin
      end
	end
end
```